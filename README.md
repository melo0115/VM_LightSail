# VM_LightSail

Step 1: Create an Amazon Lightsail account
  
  Navigate to AWS website and create a free account.

Step 2: Create a Windows Server 2019 instance in Amazon Lightsail
  
  Once your account is created
  Log into your account
  Search for LightSail service within AWS search feature
  In AWS LightSail "Click" "Create Instance"

Step 3: Config the instance

  Select Region and AZ & Zone type (Location and Redundacy)
  Choose an OS and Server Image to run your instance with
  Add a Launch script to Install specific software
  Launch Script: 
  sudo apt-get install nmap
  sudo apt-get install php
  
  Choose instance plan
  Name instance
  Add tags to instance (Optional)
  Tag Definition: "Amazon Lightsail allows you to assign labels to your resources as tags. Each tag is a label consisting of a key and an optional value that can make it more efficient to manage, search for, and filter       resources."
  Create Instance
  

Step 4: Connect to instance using the browser RDP client in Lightsail

  Click the RDP load option once instance is done provisioning
  or
  Click ellipsis and select "connect" 

  
Step 5: Get admin password for Windows Server 2019 instance

  Under the connect information section on the AWS instance page
  Click "Retrieve Default Password"
  Local Admin Password

Step 6: Get rid of created instance (No future charges)

  Final step practicing good infrastructure governance
  Delete your created instance
  Click ellipsis on instance pane
  and delete option
  "Yes, Delete"
