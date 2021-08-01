## Name: PlatformMonitor-02

## Link: https://github.com/walkjivefly/proposals/blob/master/210000/PlatformMonitor-02/PlatformMonitor-02.md

## Owner: walkjivefly

## Amount: 30000 SCA

## Hash: 3d334cb942933d1946400ec6938105c53bd01619ebf38a7fd23aefdea0ba338c

## Previous Work: 
* https://github.com/walkjivefly
* https://github.com/scalaris-project/proposals/tree/master/84000/Platform-Monitor

## Overview: 
I propose to add a number of enhancements to [Scalaris Platform Monitor](https://scalaris.platformmonitor.net/) to increase the performance and functionality. Specific improvements planned include
* using a SQL database for past orders, past proposals, servicenodes and services. This will improve performance by removing the need to scan the (possibly entire) blockchain to retrieve the information each time it is needed. Currently it is not too expensive to fetch this information directly from the scalaris-cli RPCs but as the chain grows and the number of trades, proposals and servicenodes increases the performance will gradually degrade. Keeping (only) the relevant data in an external database will improve the performance and make additional functionality possible. 
* enhance the information available on the servicenodes page to include details of the services available at each servicenode.
* change the colour scheme to match the project web page and explorer.

I will also create one or more additional Scalaris servicenodes to increase the decentralisation and resilience of the Scalaris network and the coins available for trading.

