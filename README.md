# Script to synchronize configurations in Dynatrace

An HTML page for synchronizing some configurations in Dynatrace to multiple environments with a master-slave approach. 

[Demo](https://alonsodecosio.github.io/dynatrace-sync-environments/)

# What this script can do?
The script can help you if you have multiple environments, or you are transitioning from one to another. Some of the actions that it can do are:
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/General_info.png)

## Sync Environment
Copy request attributes, tags, management zones and custom services rules to multiple environments.
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/Sync_env.png)

## Create Management Zones based on Host Groups
Analyze your environment and creates a Management Zone for each Host group that you have in the master environment that has not been defined.
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/Create_MZ.png)

## Create Synthetic HTTP Montiors based on health end-point
This section helps you create an HTTP monitor for all the services in your environment base on some filters.
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/Create_Synthetic.png)

## Convert Synthetic HTTP Monitors to/from Postman Collections
This section helps you convert and upload your Postman collection to Dynatrace synthetic and vice versa.
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/Convert_synthetic.png)

## Copy Dynatrace Users and basic Configurations
If you are not using LDAP, this section helps you copy and transfer all your user to your Dynatrace environments
![](https://github.com/AlonsoDeCosio/dynatrace-sync-environments/blob/master/img/Copy_users.png)


# How to get it setup?

1.	Download and open the page on a browser
2.	Depending on your browser configurations, you might need to enable cross-origin resource sharing
3.	Enter the URL of the environment and your token credentials
4.  Enter the information that is required for each section.
5.  Click on RUN in the section that you want to execute

If you don't want to download the code, you can always use the demo page [Demo Page](https://alonsodecosio.github.io/dynatrace-sync-environments/). If you are using managed, make sure that your environments are reachable

