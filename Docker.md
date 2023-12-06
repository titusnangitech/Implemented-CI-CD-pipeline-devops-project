- **Created an EC2 instance using Amazon Linux 2 as the Dockerhost**
  

![created an ec2 instance using amazon linux 2 of the t2 micro](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/803ffdf8-24c9-42a0-8783-3a1e36d482ea)

- **Created the Security Group to use for the DockerHost**

  
![created the docker sg d](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/008c74da-7afa-494a-b2e6-146d55c75862)

- **Choose the newly created security group**
  
![used the existing security group](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/adff9d9b-7f44-4c60-8c7f-039e344575eb)

- **Successfully cfreated the DockerHost**

  
![succeesifully created the ec2 instance](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/dae6563d-2ed0-40f0-a385-6e0a5928a199)

- **Dockerhost running**

  
![docker ec2 running](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/e483b94a-434a-414f-a487-6e28354c4637)

- Populating Mobaxterm with Dockerhost connection details**

  
![populating the MObaxterm with Docker ec2 details before connecting](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/0249dce3-2d61-4cb0-b6f0-70149e51d066)

- **Connected to Docker and swicthed to sudo user**
  
![connected to Docker  and switched to sudo user](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/de768176-8b7d-4de2-97b3-03bb48c002f4)

- **Installing Docker on the Docker host**

  
![installing docker on the docker ec2](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/800329b6-a565-40b5-bcf8-6dd3874cc2d5)

- **Checking docker status**

  
![checking docker and starting its status](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/ee71e3b2-a9bb-4b1f-88d9-ca4503d5193a)

- **Serching for a Tom Cat image to pull from Dockerhub**

  
![searching for a tom cat image to pull from dockerhub](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/720b6f97-12d1-4d93-abb3-002612a44a1c)

- **Pulled the Docker image from DockerHub**
  
![pulled the docker image from dockerhub](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/61a498da-a7c6-4beb-a8d0-f4a1ae886c7c)

- **Checking for Docker Images available in our Docker environment**

  
![checking for docker images available in our docker environment](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/6c924eb0-75ef-4f17-80e1-340b49f6990c)

- **Created a container and checking the containers available in the docker environment**

  
![created a container and checking the containers available in the docker environment](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/1c6bff29-f39a-4501-bd6b-8c2828d93527)

- **Edited a security group with the port to allow outside world to connect to the container**

  
![edited a security group with the port to allow outside to reach the container](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/d8fa3c81-3c7e-4212-9fc6-f0f3077a351e)

- **Reaching the container but displaying 404 error**
  
![reaching the container but displaying 404](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/a5ff7f58-fef0-4c7f-9802-b2bacce5c7b1)

- **Connection into the container from the docker host**
  
![connection into the container fron the docker host](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/47de69ba-923c-42a7-8dcf-fbab7ed068e3)

- **Fixed the error that was coming up when trying to connect to the container**

  
![fixed the error that was coming up when trying to connect to the container](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/ca843edc-1716-4678-a751-17af67fd301e)

- **Managed to successfully log into the tomcat container and its displaying the tomcat page**

  
![managed to succesfully log into the tomcat container and its displqying the tomcat page](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/1dbf6270-ee16-4666-8edf-ac59a33ecc4e)

- **Creating a Dockerfile**

  
![creating a dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/eee2b89b-7381-4cbf-acc6-1702d133e099)

- **Writing instructions in the Dockerfile**

  
![writing instuctuions in the dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/3f55415f-e099-4d17-8c75-aa69ee3207ae)

- **Correct Dockerfile using centos7 instead of latest**

  
![correct dockerfile using centos7 instead of latest](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/b9098057-98cf-43e7-81a8-56f101f5fb6f)

- **Created our own imgae from the Dockerfile**

  
![creating our own image from the Dockerfile   CORRECt  showing all the steps taken](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/66dcf27f-96a4-46bb-ba83-b5e7c5241ad6)

- **Created a container from the docker image created from the dockerfile**
  

![created a container from the docker image created from the dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/c7624351-b7c1-4697-bbbf-79d0289245d3)

- **Tested connection from the Browser to our container created from the Docker image from the Dockerfile**

  
![tested connection from the browser to our container created from the docker image from the focker file](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/1c73213b-34b7-4730-b4bd-aed9fd5245da)

- **Creating a new Dockerfile for the tomcat image and making changes that were causing errors**
  
![creating a new Dockerfile for our tomcat image and making changes that where causing erros](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/fdc8ca2c-feec-4e49-979a-92ab9c6d047f)

- **Building a docker image from the customed tomcat dockerfile**
  
![building a docker image from the customised tomcat dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/ac8a9c79-b637-4224-9a60-b85c9a7083c6)

- **Created a new container from the tomcat image created from the customised dockerfile**

  
![created a new container from the tomcat image created from the customized dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/8cf619e9-7985-46a6-aedc-45e0f43d547a)

- **Connecting successfully to the comntainer created from the customsed tomcat docker image**

  
![connecting successifully oto the container created from the customised tomcat docker image](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/e9abed7b-0112-4f01-95f2-37c0b9b6f619)

- **Creating and adding a new user in the docker group**
  
![creating and adding new user in the docker group](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/1710f780-393e-442f-a705-77eb738c3bed)

- **Created a user called dockeradmin**
  
![created a user called dockeradmin CORRECT](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/5a6d8355-fc06-40db-953d-5cd5873bd488)

- **Adding the new user dockeradmin to a group called docker**

  
![adding the new user dockeradmin to a group called docker](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/bd0194a0-ebfb-4273-b048-c3db0a1cd282)

- **Editing the etc sshd config to allow password login**
  
![editing the etc sshd config to allow password login](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/c71b9c08-2317-4253-aa81-413b515632b1)

- **Editing the vi etc**

  
![editing the vi etc](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/bc9e1561-d723-425d-ac73-a55d28d8e278)

- **Reloading the sshd service after editingthe file**
  
![reloading the sshd service after editing the file](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/2b88dec6-b5b1-4837-bfb1-69a4b8c7176d)

- **Installing the Publish Ovewr SSh plugin**

  
![installing the publish over ssh plugin](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/aae649ff-a796-4b16-bd3d-236fa463cd6a)

- **Configuring Dockerhost with Jenkins using private Ip and password of the admin user**

  
![configuring dockerhost with jenkins using private ip address and password of the admin user that we cfreated in the docker group](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/c41f623f-b2d9-46ac-a146-fca58dd5cbed)

- **Created a Jenkins job to build and copy artifacts on to DockerHost**

  
![created a jenkins job to build and copy artifacts on to dockerhost](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/444eccb2-5072-4ebf-9a6f-ce8975eff520)

- **Created a directory called Docker by the root user and gave permisson to docker admin**

  
![exited the dockeradmin profile to root and created a directory called docker by the root user and gave permission to dockeradmin](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/50fd3478-634a-44a4-befe-717f1761c6cc)

- **Moving the Dockerfile from root directory into the docker directory created and changing owvership**

  
![moving the Dockerfile from root directory into the docker directory we created and changing ownership to dockeradmin](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/9646b9fa-7d29-4a3c-8e8c-e2961da395d2)

- **Changing the folder where to place an artifact in the Dockerhost**

  
![changing the folder where to place an artifact in the dockerhost](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/9432cd0b-884f-46f4-bdc3-8744b2229473)

- **Copying the war fule after running the jenkins pipeline**

  
![war file has been copied after running the jenkins pipeline](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/ad09121c-8e42-4c02-b67c-4d8ad97e61c2)

- **Vi into the dockerfile**

  
![vi in nto the dockefile and copy the artifact which is in the same folder with the dockerfile and put it into the dockerfile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/6a752ba4-5c8e-44b9-b7ee-c456bc65fd00)

- **Vi into Dockerfile**

  
![vi into Dockefile](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/711e5bc8-f684-4d3d-9e8d-11eec4275d88)

- **Building a Docker image from the Docker file**

  
![building a docker imgae from the docker file and the dockefile contains the docker image from docker registry and also artifact from jenkins](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/d195ad2b-be8b-4990-a24d-d45fea39f904)

- **Checking if the image is created**

  
![checking if image is created](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/1398f2d5-e887-4e1a-b650-f9b020d98bf4)

- **Created a container from the Docker image with the artifact**

  
![created a container from the docker image that has the artifact inside](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/07ec4ca4-e25b-43fc-9359-2513c27f737c)

- **Accessing the container through port 8086**

  
![accessing the container through port 8086](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/43f83554-ba18-4ae7-8887-fe73ea563454)

- **CHecking if we can access our app within the container through the web using port 8086**

  
![checking if we can access our app within the container through the web using port 8086](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/7bd1ff48-d8b0-4c09-8d4e-12d35955e952)

- **Populating Jenkins with Docker commands to automate the building and deployment**

  
![populating jenkins with docker commands to automate the building and deployment](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/b1acff4d-06f0-4eab-835b-258009162912)

- **Checking if the build is a success by automation**

  
![checkimg if build and deployment is a success by automation](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/81bc1e7c-b787-4187-a2ba-db85cae0ab2a)

- **Jenkins job to automate CICD to deploy application on Docker container**

  
![jenkins job to automate cicd to deploy application on deocker container](https://github.com/titusnangitech/Implemented-CI-CD-pipeline-devops-project/assets/128609800/8949d481-23a8-4457-bf78-6125c8a2a038)
