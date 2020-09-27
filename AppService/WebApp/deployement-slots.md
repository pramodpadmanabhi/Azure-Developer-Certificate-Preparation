# Deployment Slots
* Deployment Slots has the same hostName as live production app
* Provides Service-Interruptions
* Cold-Starts can be prevented
* Clones the App Configurations but not code which needs to deployed again 

##### Deployment Slots and Tiers
  
  | Tier      | Maximum Slots |
  |-----------|---------------|
  | Free      | 0             |
  | Shared    | 0             |
  | Basic     | 0             |
  | Standard  | 5             |
  | Premium   | 20            |
  | Isolated  | 20            |

* AppService warms-up the app by sending a request to the root of the site
* Host Names are not shared between deployment slots

# Configure Slot Settings
* Configuration can be set Slot using Application Settings in Configuration Page
* Connection Strings can also be Set
