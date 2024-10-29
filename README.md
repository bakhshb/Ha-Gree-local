# Ha-Gree-local

# Adoting the code from this [Repo](https://github.com/rapi3/HA-OS-Gree/tree/main) to resolve the original gree status update issue
 
**HACS installation:**

search on HACS integration for Gree climate integration that work from another LAN segment / you can specify AC IP address or add manual the repository:

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
