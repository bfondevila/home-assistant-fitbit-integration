# Fitbit integration for home assistant

Based on [home assistant fitbit integration](https://github.com/home-assistant/core/tree/dev/homeassistant/components/fitbit), started from commit hash [f83c8de8d3df745bc855be989ac307667c265ad0](https://github.com/home-assistant/core/commit/f83c8de8d3df745bc855be989ac307667c265ad0).

## Configuration

Follow [home assistant's official fitbit integration documentation](https://www.home-assistant.io/integrations/fitbit/).

## Polling frequency

This integration reduces the number of sensors pulled, and in exchange increases the polling frequency to every 5 minutes.
Only sensor that is currently being pulled is battery (and states such as "battery charging / discharging").
