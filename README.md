# unbound-get-root-hints

simple systemd timer to periodically update root.hints for unbound recursive resolver

## Usage

* Download the service files:
```
cd /etc/systemd/system/
sudo wget https://raw.githubusercontent.com/saint-lascivious/unbound-get-root-hints/master/get-root-hints.service
sudo wget https://raw.githubusercontent.com/saint-lascivious/unbound-get-root-hints/master/get-root-hints.timer
```

* Enable and start the service
```
sudo systemctl enable get-root-hints.timer
sudo systemctl start get-root-hints.timer
```

## Contact
* Discord
[SaintLascivious](https://discord.gg/NC7taVyn)

* Email
saint@sainternet.xyz

* IRC
[##saint-lascivious](https://webchat.freenode.net/##saint-lascivious)

* Reddit
[saint-lascivious](https://www.reddit.com/user/saint-lascivious)

![alt text][logo]

[logo]:https://vignette.wikia.nocookie.net/pokemon/images/7/76/265Wurmple.png "Using the spikes on its rear end, Wurmple peels the bark off trees and feeds on the sap that oozes out. This Pokémon's feet are tipped with suction pads that allow it to cling to glass without slipping."
