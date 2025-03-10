   
   # Notes for Ultimate DevOps Project and Resume Preparation Udemy Course

- This repository contains the complete notes for the Ultimate DevOps Project and Resume Preparation course prepared by `Abhishek Veeramalla` on Udemy.

- Documentation is organized in Sections, the same way how videos are organized in the udemy course.

- Refer for Project Documentation - https://opentelemetry.io/docs/demo/

## Notes from Srikanth for Practice

### Pre-requisites

**1. Install Docker**

* Refer docker docs for Installation - https://docs.docker.com/engine/install/ubuntu/

**2. Install Kubectl**

* Refer Kubernets docs for Installation - https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/

**3. Install Terraform**

* Refer Terraform Docs for Installation - https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

### Run the APP Locally by docker compose

* In this app the docker compose file is readily available so first execute that and check app is accessible or not.

```shell
docker compose up
docker ps -a
docker container ps
docker compose down
```
* It will take some time has it has lot of containers
* try accessing ipaddr:8080
* After that make sure down all containers by DOWN command.

### Docker 
* Next normally we have to containerize the app
* It has 21 micro services , so to learn select some ms with different lanhuages - **go,python,java**

**1. product catalog**
* This is devloped in *go lang*
* First run this locally and follow instructions from file / dev team
* Install go lang, build and run the app
```shell
sudo apt update
sudo apt install golang-go
go build -o product-catalog .
go run .
```
* This will run on terminal only.
