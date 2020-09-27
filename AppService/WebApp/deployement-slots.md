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
