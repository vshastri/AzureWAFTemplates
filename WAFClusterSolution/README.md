# WAFClusterSolutionTemplate

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

What does this Solution Deploy? 

Cluster of Barracuda Web Application firewall. Ranging from 1 to n. You get to define the number of instances in the cluster 
Azure Public Load Balancer 
      NAT Rule to access each instance
	  HTTP and HTTPS Load balancing rules

How to access deployed WAF instances?

 First instance will be avalable http://elbdnsname:8000 , second one on http://elbdnsname:8001 and so-on. 



