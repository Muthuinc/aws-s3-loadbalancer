1.) Two EC2 instances has been launched from my Own Vpc in two different availablity zones.
 a.) nginx webserver is installed in both instances
 b.) sample file is added to view the differences.

2.) Application load balancer has been created with the target group pointing the
    above two instances.
3.) URL for the loadbalancer obtained.
4.) When the user hit the URL the load balancer distribute the load to both the instances
    each at a time.
5.) This way we can prevent our application from the server crash.