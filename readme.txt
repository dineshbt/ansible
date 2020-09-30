after running setup-lb.yml and accessing loadbalancer was giving permission issue.
Note: see apche error log to see the details.
after running the below command it resolved the issue

/usr/sbin/setsebool -P httpd_can_network_connect 1