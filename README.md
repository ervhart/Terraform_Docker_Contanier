# Prerequistes
* Install Docker Engine for your Linux distribution.   
* Create a directory named terraform-docker-container.
* Then, navigate into  terraform-docker-container.
* Create a main.tf file or use the one above
* Initialize the project, which downloads a plugin that allows Terraform to  interact with Docker(terraform init).
* Provision the NGINX server container with apply. 
* When Terraform asks you to confirm type yes and press ENTER.
* Verify the existence of the NGINX container by visiting localhost:8000 in your web browser or running docker ps to see the container.
* To stop the container running, type terraform destroy
