# Duplex Home Assistant Configuration
Configuration for Home Assistant (https://home-assistant.io/)

## Integrations in use:

 * Running on Raspberry Pi 3B+
 * Linear HUSBZB-1 Zigbee/Z-Wave stick
 * Xiaomi hub - motion/temperature sensors
 * Nest - climate control
 * Flux - lighting temperature
 * Darksky - weather
 * iOS - presence and notifications

## Automations

### Persistent

 * Turn of office light if motion. Turn off if 3 minutes of inactivity
 * Send notification if garage door is left open for 5 minutes
 * Turn on lights if coming home after dark

### Vacation Mode

 * Turn on and randomize lights
 * Send notification if presence detected

## Notifications

 * Notify if headed home, to manually turn on climate
