2- Create a pod with the name redis and with the image redis 
<img width="653" alt="Screenshot 2024-07-13 235055" src="https://github.com/user-attachments/assets/261b6a15-4c89-4889-b1ba-ba0d565c95b9">
3- Create a pod with the name nginx and with the image “nginx123” Use a pod-definition YAML file. 
<img width="658" alt="Screenshot 2024-07-13 235229" src="https://github.com/user-attachments/assets/fe44b85b-11b8-4dd7-beba-0386dbaf5130">
<img width="650" alt="Screenshot 2024-07-13 235322" src="https://github.com/user-attachments/assets/96227274-ffe1-4504-a962-892f7dedee28">
5- Change the nginx pod image to “nginx” check the status again 
<img width="647" alt="Screenshot 2024-07-13 235434" src="https://github.com/user-attachments/assets/765d7c65-b89a-45cc-b0b7-00a1ddd39179">
<img width="653" alt="Screenshot 2024-07-13 235404" src="https://github.com/user-attachments/assets/1ee66a58-bdf0-4d5f-88e9-fa768936407d">
6- How many ReplicaSets exist on the system? 
<img width="656" alt="Screenshot 2024-07-13 235543" src="https://github.com/user-attachments/assets/f8257008-a97a-4fd0-b2b7-76c6d9c06c49">
7- create a ReplicaSet with name= replica-set-1 image= busybox replicas= 3 
<img width="638" alt="Screenshot 2024-07-14 000000" src="https://github.com/user-attachments/assets/36cbd35e-2661-4c65-98cb-ebf7a1a0ff77">
<img width="656" alt="Screenshot 2024-07-13 235850" src="https://github.com/user-attachments/assets/af813441-b597-4755-9e3a-e985a673c9c3">
8- Scale the ReplicaSet replica-set-1 to 5 PODs. 
<img width="656" alt="Screenshot 2024-07-14 000052" src="https://github.com/user-attachments/assets/1dfefb22-f664-44e6-b51e-ce4a3f481cc5">
10- Delete any one of the 5 PODs then check How many PODs exist now? Why are there still 5 PODs, even after you deleted one?
<img width="653" alt="Screenshot 2024-07-14 000220" src="https://github.com/user-attachments/assets/054b0202-f551-4393-add6-03d2d8cb0675">
11- How many Deployments and ReplicaSets exist on the system? 
<img width="649" alt="11" src="https://github.com/user-attachments/assets/443fa997-e975-4b14-9fa6-a8605320d529">
12- create a Deployment with name= deployment-1 image= busybox replicas= 3 
<img width="655" alt="12" src="https://github.com/user-attachments/assets/32b8ae60-1fb1-4f50-93db-a62c07965188">
13- How many Deployments and ReplicaSets exist on the system now? 
<img width="646" alt="13" src="https://github.com/user-attachments/assets/9135daf5-9ec7-444c-9e74-edd5e2b86f2c">
14- How many pods are ready with the deployment-1? 
<img width="646" alt="14" src="https://github.com/user-attachments/assets/efe7e575-37d5-43d5-a2bd-6311dd16b099">
15- Update deployment-1 image to nginx then check the ready pods again 
<img width="601" alt="15-2" src="https://github.com/user-attachments/assets/1a912bc0-175d-4374-a976-ce915cbc4096">
<img width="650" alt="15-1" src="https://github.com/user-attachments/assets/a195be9c-6a3f-430d-9a7e-171bd14dc671">
16- Run kubectl describe deployment deployment-1 and check events What is the deployment strategy used to upgrade the deployment-1? 
<img width="446" alt="16" src="https://github.com/user-attachments/assets/fefd3d81-5a96-46c9-b70e-58924b08d780">
17- Rollback the deployment-1 What is the used image with the deployment-1? 
<img width="649" alt="17" src="https://github.com/user-attachments/assets/590a4589-acc9-45d3-8b40-5cf0c63f6330">
18- Create a deployment using nginx image with latest tag only and remember to mention tag i.e nginx:latest and name it as nginx-deployment. App labels should be app: nginx-app and type: front-end. The container should be named as nginx-container; also make sure replica counts are 3. 
<img width="650" alt="18-2" src="https://github.com/user-attachments/assets/c4da49ae-5297-4270-b0c1-6a099701a8c1">
<img width="656" alt="18-1" src="https://github.com/user-attachments/assets/03747781-67ff-4113-b0fe-5985f14104b5">
