Centralized Management Initiative
===

Purpose
--
Store here all the policies should be included in this initiative to collect data from RP on all subscription that must be centralized to strike the right balance between observability, data protection, access and management.
Even more creation of Log Analytics Workspace should be centralized in the management subscription to ensure the right data protection, efficiency, security and visibility for all infrastructures things that are centrally managed (network RPs, activityLog, AD Signins Logs)

A tentative list of those resources is:
 - ------------                             
 Microsoft.Network/networkSecurityGroups   
 Microsoft.Network/publicIPAddresses        
 Microsoft.Network/connections              
 Microsoft.Network/expressRouteCircuits     
 Microsoft.Network/loadBalancers            
 Microsoft.Network/applicationGateways      
 Microsoft.Network/virtualNetworks          
 Microsoft.Network/azureFirewalls           
 Microsoft.Network/privateEndpoints         
 Microsoft.Network/virtualNetworkGateways   

Creation of the following resource should be also denied on all subscription
microsoft.insights/components  
microsoft.insights/workspaces

Exception can be made for vertical workloads in dedicated landing zones.
