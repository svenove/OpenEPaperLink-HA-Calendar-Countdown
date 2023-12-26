# OpenEPaperLink-HA-Calendar-Countdown
Inspired by [chunkysteveo's Christmas Countdown](https://github.com/chunkysteveo/OpenEPaperLink-HA-Christmas-Countdown), I created a more general countdown, which utilizes the HASS local calendar to count down to whatever is next.

![2023-12-25 23 04 56](https://github.com/svenove/OpenEPaperLink-HA-Calendar-Countdown/assets/4579212/6dc3b883-bdb2-4523-bbb5-b168683d04ea)


## Integrations needed:
* https://github.com/jonasniesner/open_epaper_link_homeassistant (Install via HACS)
* https://www.home-assistant.io/integrations/local_calendar/ - Local calendar

## Initial setup
1. Add the integration "Local calendar" and name the calendar "epaper_countdown".
2. Create a new automation from the [2.9_automation.yaml](https://github.com/svenove/OpenEPaperLink-HA-Calendar-Countdown/blob/main/2.9_automation.yaml) 
(remember to replace the eTag-entity and any local translations of the few words in it). 
3. From the sidebar, go to "calendar" and add a few events:
* Summary: the name of the event
* Description: The [MDI-icon](https://pictogrammers.com/library/mdi/) to use
* All-day event
* Start: guess...
* Repeat: yearly for birthdays, etc

![image](https://github.com/svenove/OpenEPaperLink-HA-Calendar-Countdown/assets/4579212/09bf8aff-eba6-422a-9fae-35d280352aa6)

