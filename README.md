# Lab 4&5 --- Docker Intro
## Discribe how to build and start the system
  **1. Build image using [docker build -t ‘testflask’] .**
  ![image](https://github.com/kafkaontheshore5997/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Week4Imgs/Lab4DockerBuild.PNG)
  **2. Run the container using docker run -d -p 5000:5000 testflask** <br>
  **3. If I run [docker ps -a] :**
  ![image](https://github.com/kafkaontheshore5997/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Week4Imgs/Lab4DockerPs-a.PNG)
  **4. Go to localhost:5000 on the browser:**
  ![image](https://github.com/kafkaontheshore5997/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Week4Imgs/lab4Browser.PNG)
  **5. Output on Docker GUI:**
  ![image](https://github.com/kafkaontheshore5997/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/Week4Imgs/Lab4DockerGUI.PNG)
  
## Briefly summarize the differences between Docker and Virtual Machine.
1. Each VM has a separate OS, whereas each Docker container can share OS.
2. For process isolation: VM is hardware-level, whereas docker container is OS-level.
3. Creating a Docker container takes seconds, whereas creating a VM takes longer time.
4. Containers are lightweight, whereas VM can be few GBs.
