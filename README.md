# Project 4

## Steps completed:

1. Launch your Virtual Machine with your Udacity account
2. Follow the instructions provided to SSH into your server
3. Create a new user named grader (password: thiswouldbemoresecureinreallife)
4. Give the grader the permission to sudo
5. Update all currently installed packages
6. Change the SSH port from 22 to 2200
7. Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
8. Configure the local timezone to UTC
9. Have installed Apache2, but not configured with mod_wsgi yet (29 June)

a. Installed `cron-apt` to automatically update packages, and `unattended-upgrades` to

## Steps outstanding

9. Install and configure Apache to serve a Python mod_wsgi application
10. Install and configure PostgreSQL:
  Do not allow remote connections
  Create a new user named catalog that has limited permissions to your catalog application database
11. Install git, clone and setup your Catalog App project (from your GitHub repository from earlier in the Nanodegree program) so that it functions correctly when visiting your server’s IP address in a browser. Remember to set this up appropriately so that your .git directory is not publicly accessible via a browser!


12. Create README
  Your README.md file should include all of the following:
  i. The IP address and SSH port so your server can be accessed by the reviewer.
  ii. The complete URL to your hosted web application.
  iii. A summary of software you installed and configuration changes made.
  iv. A list of any third-party resources you made use of to complete this project.

13. Open your ~/.ssh/udacity_key.rsa file in a text editor and copy the contents of that file. During the submission process, paste the contents of the udacity_key.rsa file into the "Notes to Reviewer" field.
