# home-assistant-blueprint-frient-keypad
Blueprint inspired in [AndrejDelany version](https://community.home-assistant.io/t/zigbee2mqtt-sync-keypad-and-alarm-control-panel-states/345311) for frient keypad /  Develco KEYZB-110 for manual alarm control panel integration in home assistant.

- Night mode support added
- SOS/emergency action
- Multiple RFID codes (using MIFARE Classic 1K 13,56 Mhz)

## FAQ:
### How to retrieve rfid code using keypad?
- Bring closer the tag to keypad and push any action button (for example disarm, arm night, disarm). Visit Zigbee2MQTT console log and search the "action_code" in the payload received.

## TODO:
- No code required for arming
- ...
