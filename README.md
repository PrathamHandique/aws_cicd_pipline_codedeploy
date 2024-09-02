<img width="400" height="250" alt="Screenshot 2024-09-02 at 6 00 48 PM" src="https://github.com/user-attachments/assets/6b5472d5-850e-49e9-be0c-f98eee8c38f7">
<img width="400" height="250" alt="Screenshot 2024-09-02 at 6 00 58 PM" src="https://github.com/user-attachments/assets/69abe89e-7909-4edc-bb6e-fa53a18c9bce">






<b>User Data for Dependencies installations for AMAZON Linux 2:-</b>

#!/bin/bash<br />
sudo yum -y update<br />
sudo yum -y install ruby<br />
sudo yum -y install wget<br />
cd /home/ec2-user<br />
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install<br />
sudo chmod +x ./install<br />
sudo ./install auto<br />
sudo yum install -y python-pip<br />
sudo pip install awscli<br />
