# SSO sample
In here, you'll see how to implement SSO between Single Page Apps and Regular Web Apps using Auth0.

# Structure
In this example, we have 3 applications:
app1.com (single page app)
app2.com (single page app)
app3.com (regular web app)

Each application has its own folder in this repository with its own instructions on how to run it. 

# Running

In order to be able to test SSO correctly, each application must have its own domain. For that, you can edit your `/etc/hosts` and make app1.com, app2.com and app3.com all point to `127.0.0.1`.

For that, open `/etc/hosts` and edits as follows:

````
# Host Database

# localhost is used to configure the loopback interface
# when the system is booting.  Do not change this entry.

127.0.0.1 localhost
255.255.255.255 broadcasthost
::1             localhost 

127.0.0.1 app1.com
127.0.0.1 app2.com
127.0.0.1 app3.com
````

Once that is done just run all 3 applications as per the instructions on each README and go to http://app1.com:3000 to start using the applications.