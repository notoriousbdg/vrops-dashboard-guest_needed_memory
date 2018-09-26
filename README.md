# VMs with Guest Needed Memory not Collecting Dashboard for vRealize Operations 6.7
---------

Identify VMs that are not collecting Guest Needed Memory metric that's used by the [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) capacity engine.  Included is a dashboard and optional alerts.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Dashboard.png)

## Alerts and Recommendations
![Alerts](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Alerts.png)
![Recommendations](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Recommendations.png)

## Installation
1. Import the super metric at `Administration` / `Configuration` / `Super Metrics` / `Import Super Metric`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Import_Super_Metric.png)
2. Click `Browse...` then select the file named [SuperMetric - Guest Needed Memory is not collecting.json](https://github.com/notoriousbdg/vrops-dashboard-guest_needed_memory/raw/master/SuperMetric%20-%20Guest%20Needed%20Memory%20is%20not%20collecting.json)
3. Edit the Policy at `Administration` / `Policies` / `Policy Library`.  The policy should be `vSphere Solution's Default Policy (DATE)` unless a new policy was explicitly created.  
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Policy_Library.png)
4. Enable `Super Metric|Guest Needed Memory is not collecting` metric for Virtual Machine object type only  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Policy_Metrics.png)
5. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Import_View.png)
6. Click `Browse...` then select the file named [Views - VMs with Guest Needed Memory not Collecting.zip](https://github.com/notoriousbdg/vrops-dashboard-guest_needed_memory/raw/master/Views%20-%20VMs%20with%20Guest%20Needed%20Memory%20not%20Collecting.zip)
7. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Import_Dashboard.png)
8. Click `Browse...` then select the file named [Dashboard - VMs with Guest Needed Memory not Collecting.zip](https://github.com/notoriousbdg/vrops-dashboard-guest_needed_memory/raw/master/Dashboard%20-%20VMs%20with%20Guest%20Needed%20Memory%20not%20Collecting.zip)
9. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Dashboard_List.png)
10. *Optional* Import the alerts at `Alerts` / `Alert Settings` / `Alert Definitions` / `Import`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-guest_needed_memory/master/Import_Alert.png)
11. *Optional* Click `Browse...` then select the file named [Alert Definitions - VMs with Guest Needed Memory not Collecting.xml](https://github.com/notoriousbdg/vrops-dashboard-guest_needed_memory/raw/master/Alert%20Definitions%20-%20VMs%20with%20Guest%20Needed%20Memory%20not%20Collecting.xml)

## Support

This dashboard requires vRealize Operation 6.7.x (or newer) Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-guest_needed_memory/issues) for feedback.
