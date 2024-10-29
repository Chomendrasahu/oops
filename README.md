# oops
Task 1. Create a Linux VM instance
Create a Linux virtual machine, name it Instance name and specify the zone as Compute zone.
Task 2. Enable public access to VM instance
While creating the Linux instance, make sure to apply the appropriate firewall rules so that potential customers can find your new product.
Click Check my progress to verify the objective.

Create a Compute Engine instance, add necessary firewall rules.

Task 3. Running a basic Apache Web Server
A virtual machine instance on Compute Engine can be controlled like any standard Linux server.

Deploy a simple Apache web server (a placeholder for the new product site) to learn the basics of running a server on a virtual machine instance.
Click Check my progress to verify the objective.

Add Apache2 HTTP Server to your instance

Task 4. Test your server
Test that your instance is serving traffic on its external IP.
You should see the "Hello World!" page (a placeholder for the new product site).

Click Check my progress to verify the objective.

Test your server

Troubleshooting
Receiving a Connection Refused error:
Your VM instance is not publicly accessible because the VM instance does not have the proper tag that allows Compute Engine to apply the appropriate firewall rules, or your project does not have a firewall rule that allows traffic to your instance's external IP address.
You are trying to access the VM using an https address. Check that your URL is http:// EXTERNAL_IP and not https:// EXTERNAL_IP.
Congratulations!
