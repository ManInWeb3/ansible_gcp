# ansible_gcp


What the roles do:
 - Create new GCP CE virtual server 
 - Add needed DNS records to GCP DNS
 - Add and configure Databases (dumps can be stored in the same GIT repository with congfig templates and this ansible roles)
 - Creat and save configs from templates (templates stored in GIT)
 - Get applications source code (from git repo) and install it
 - In SLIM API role you can find example how to obtain free Let's encrypt certificates

These roles don't install any software, because they work with image and all the software installed and tested in the image. 
