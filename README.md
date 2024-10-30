# Ha-Gree-local

# Adoting the code from this [Repo](https://github.com/rapi3/HA-OS-Gree/tree/main) to resolve the original gree status update issue
 
**HACS installation:**

search on HACS integration for Gree climate integration:

1. Go to Home Assistant and navigate to HACS.
2. In HACS, Click on the three dots button in the upper right corner and select "Custom repositories".
4. In the window that appears, enter the URL of this repository
     ```
        https://github.com/bakhshb/Ha-Gree-local
   ```
5. and select the category (Integration).
6. Click on "Add".


**Manual instalation:**

copy all from `` gree`` to ``custom_components/gree/``
restart HA
check log for errors

**Set-up:**
If no errors then go to Settings - Devices & Services- Add integration - Gree Climate and your AC will be discovered automaticaly.


If AC it is find and set-up OK check your Gree Climate - Integration entries and rename switches if required, you can find the switch name in core.entity_registry:
- "entity_id": ``switch.MAC_none`` -> Panel Light
- "entity_id": ``switch.MAC_none_2`` -> _Quiet_
- "entity_id": ``switch.MAC_none_3`` -> _Fresh Air_
- "entity_id": ``switch.MAC_none_4`` -> _XFan_
- "entity_id": ``switch.MAC_none_5`` -> _Health mode_

***DONE***
