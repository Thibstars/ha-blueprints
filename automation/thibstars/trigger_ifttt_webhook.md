# Trigger IFTTT Webhook #
Trigger a IFTTT webhook.

## Context ##
Use this blueprint for automations that will trigger an IFTTT Webhook.

Make sure to include your IFTTT API key to the configuration.yaml file:
````yaml
# IFTTT
ifttt:
  key: <api_key>
````

For more information, head to the [documentation](https://www.home-assistant.io/integrations/ifttt/).

## Inputs ##
- IFTTT event name: This value must match the event name as configured in the IFTTT applet.