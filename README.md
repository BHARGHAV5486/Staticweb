#STATIC WEBSITE
log into AWS Console
Select t2 micro linux instance
Create a new key pair
Open ssh & http ports
launch EC2 instance
Copy instance DNS name@ User name
Paste it in Mobaxterm ssh remote section
Use key pair in Advanced ssh key settings
Using  Linux instance we need to type Commands like
sudo su -
yum update -y
yum install httpd -y
yum install git -y
Service httpd start
chck confih httpd on
Use Git URL link 
git clone " code link "
we can see  index.html 
copy this file to /var/www/html
cp index.html /var/www/html





