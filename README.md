# linux_server_config_project_5

Catalog app deployed on a linux server running Ubuntu 14.04.1 with appropriate modifications, configurations and installations of required packages and libraries

## Server IP: 52.11.56.253 SSH Port: 2200

In order to ssh as user grader please use command:
ssh -p 2200 -i path to/udacity_key.rsa root@52.11.56.253

## Configurations and Changes

-Created new server user
-Changed SSH PORT
-Configured Firewall
-Modified timezone
-Installed required dependencies and libraries
-Reconfigured existing app to use PostgreSQL instead of SQLite and created additional user
-Made changes to oauth paths and redirects 

## Third party resources

guide at: https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
docs at: http://docs.sqlalchemy.org/en/rel_1_0/core/engines.html
