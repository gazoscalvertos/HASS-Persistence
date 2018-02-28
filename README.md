# Home Assistant - Persistence!
## Intro :-)
<img align="right" width="376.5" height="525" src="https://github.com/gazoscalvertos/Hass-Custom-Alarm/blob/master/BTC.png">

Welcome my fellow modders, tinkerers, home assistant wizards!!

Consider donating to this project to keep it going as anything contributed will be placed back in to development of home assistant custom modules etc.

## Features
- Saves the state of any entity (sensor, input_text, input_boolean etc) defined in the configuration yaml. 
- Restores the saved state for example after home assistant has been restarted or has recovered from a power failure

## Coming Soon
- Ability to use Domain to save all entities within a domain (Sensors, input_text, input boolean etc)

## Installation Guide
To get this running add the file (custom_components/sensor/persistence.py) from this repo into your home assistant configuration directory, then add the following to your configuration.yaml file under the sensor configuration:

```
sensor:
  - platform: persistence
    entities: #ADD ALL OF YOUR ENTITIES HERE
      - input_text.test 
      - input_boolean.test2
```
### Testing
- Tested on HA v0.63.2

### Changelog
- (28/02/18) Intial upload

## Note!
Beware, here be dragons! There may be bugs, issues whilst I get this off the ground. Hopefully we can conquer these in due course!..

## Thanks!
Consider supporting this project and donate! All funds will go towards bringing new features, hardware support and bug squashing!!

- BTC Address: 1NFeyzpKKiKbBYSmCLQZQLxBqJbhSbqmwd
- LTC Address: LTUViN3QUESkQk3mG2hvTzhLRQPVAd269f
- XRP Address: rwuMp76ht6dmGvipxwKr5ZE6VpF7ZKC7qs
- ETH Address: 0xCbeD2D2cf0434370c1ca126707009b876b736609
- Paypal: ha.custom.alarm@gmail.com