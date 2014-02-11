Zero-Downtime Deployments for Grails
=============
```bash
git clone https://github.com/andreassimon/zero-downtime.git
cd zero-downtime
bundle install
librarian-chef install
vagrant up
```
Assuming you have a WAR file in the project directory:
```bash
vagrant ssh
sudo -i
deploy-war /vagrant/your-war-file.war
```
