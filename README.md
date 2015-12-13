## Run your own docker registry using Amazon S3 for data storage

- How to run a "normal" registry: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-private-docker-registry-on-ubuntu-14-04

- Run registry (top level used images are: nginx:1.9 and registry:2):
```
	# docker-compose up
```
- Login (using https):
```
	# docker login https://YOURDOMAIN
	Login Succeeded
```
