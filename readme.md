# Duplex Home Assistant Configuration
Configuration for Home Assistant (https://home-assistant.io/)

## Overview
 * Running on a KVM virtual machine on the homelab rack server, ProLiant DL385 G7 6176
 * Raspberry Pi Zero W with camera for outside monitoring
 * 2 Raspberry Pis with bluetooth for full house presence monitoring
 * Raspberry Pi for hot-tub temperature monitoring

## Integrations in use:

 * Linear HUSBZB-1 Zigbee/Z-Wave stick - lights and door sensors
 * Xiaomi hub - motion & temperature sensors
 * Nest - climate control
 * Alexa - notifications, control, and media
 * Darksky - weather
 * iOS - presence and notifications
 * BLE monitor - presence
 * Xiaomi vacuum

## Notes

### Naba Casa
Lazy Alexa integration
https://www.nabucasa.com/config/amazon_alexa/

### Alexa media
Custom component to push notifications to Alexa and control media from the UI
https://github.com/keatontaylor/alexa_media_player/

### BLE Monitor
Monitor device presence using bluetooth scans
https://github.com/andrewjfreyer/monitor/

### Custom Hot-tub Temperature Sensor - TEMPer1F
Raspberry pi with external temperature sensor pushing updates over MQTT