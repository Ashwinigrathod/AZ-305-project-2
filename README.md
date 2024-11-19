# AZ-305-project-2     ( deploying Azure protected Geo-Redundant Solution having path based routing )
this project is for Globally Distributed Appication with highly secured architecture
created vnet in 2 different region, and created VM as web server in both region
provisioned application gateway with path based routings by adding frontend and backend IP addesses
with the help of traffic manager distributed thr traffic based on priority
finally added application gateway to the traffic manager  endpont 
by using DNS of traffic manager endpoint we can see the distribution of traffic to the web servers 
