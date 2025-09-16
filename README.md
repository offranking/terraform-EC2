# terraform-EC2
### Terraform EC2 Instance with key Pair and UserData 


### Log in to AWS and use your SSH key to access the instance from the terminal.”
<img width="915" height="585" alt="Screenshot 2025-08-17 at 12 47 54 pm" src="https://github.com/user-attachments/assets/ee67fec4-ff09-46e0-b1e5-13c35bbabea4" />

### Create an IAM User for Terraform in AWS Console
Log in to your AWS Management Console, In the search bar, type IAM and navigate to the IAM (Identity and Access Management) service. <img width="752" height="187" alt="Screenshot 2025-08-17 at 12 45 59 pm" src="https://github.com/user-attachments/assets/1858a4d3-1ea8-4c15-9f83-7300e29f7144" />

### Login on your terminal UBUNTU ROOT.
<img width="1440" height="900" alt="Screenshot 2025-08-17 at 12 50 20 pm" src="https://github.com/user-attachments/assets/f9eb2213-dd53-4799-82df-d2867b6ca000" />

### Create a new project directory and name it "terraform-ec2-keypair"
"terraform-ec2-keypair"
<img width="935" height="60" alt="Screenshot 2025-08-17 at 12 53 15 pm" src="https://github.com/user-attachments/assets/d064e06b-47eb-43fc-a956-8c8cd75c321e" />

### Ls to ensure that the directory is being created and cd into it 
<img width="866" height="58" alt="Screenshot 2025-08-17 at 12 55 40 pm" src="https://github.com/user-attachments/assets/34135e23-36e1-48f5-b6be-2abf72a13567" />

### Create a terraform configurations file by Using nano main.tf or touch main.tf
<img width="974" height="84" alt="Screenshot 2025-08-17 at 12 58 24 pm" src="https://github.com/user-attachments/assets/6dc82a88-e75b-42f8-8dcb-13c775e72258" />

### Open the files and put in your terraform code inside the file 

<img width="967" height="768" alt="Screenshot 2025-08-17 at 1 14 44 pm" src="https://github.com/user-attachments/assets/834b9009-5ad9-4f78-a53b-6fbbc6f831aa" />

### After paste in the code inside the terraform configurations files run the command "terraform init"
<img width="1055" height="407" alt="Screenshot 2025-08-17 at 1 17 18 pm" src="https://github.com/user-attachments/assets/076d06e5-48f5-4e51-a8eb-0ed922bd5197" />

### on this part we need to run "terraform validate"
<img width="934" height="121" alt="Screenshot 2025-09-16 at 4 51 36 pm" src="https://github.com/user-attachments/assets/02141119-8930-49ca-a90e-c58bb1067673" />

### After running terraform validate to ensure the configuration is correct, run terraform plan. This command creates an execution plan, showing you the resources Terraform will create, modify, or destroy. Review the plan carefully to confirm everything looks as expected before applying the changes

<img width="1081" height="204" alt="Screenshot 2025-09-16 at 4 53 26 pm" src="https://github.com/user-attachments/assets/a8454dec-429d-42a3-96d7-6f9ad78b0563" />



### For this part of the project, you need to run terraform apply. This command takes the execution plan (similar to what you see when you run terraform plan) and carries it out by creating, updating, or destroying resources as defined in your configuration. When you run terraform apply, Terraform will first show you the proposed changes and ask for confirmation—type yes to proceed. Once confirmed, Terraform provisions the infrastructure and, when complete, displays the outputs you defined.

<img width="1436" height="853" alt="Screenshot 2025-09-16 at 4 24 54 pm" src="https://github.com/user-attachments/assets/8f209825-fc92-49e6-a8e9-eec3064b4304" />


<img width="1436" height="856" alt="Screenshot 2025-09-16 at 4 26 22 pm" src="https://github.com/user-attachments/assets/93bf296d-30ba-473f-8e14-a4e82ef41b6a" />


### Copy public_ip = "54.83.184.30"
<img width="1412" height="501" alt="Screenshot 2025-09-16 at 4 28 57 pm" src="https://github.com/user-attachments/assets/d6322ca3-987c-4634-b05b-23932b23b065" />


### On the public_ip = "54.83.184.30" on your web browser you will get this result 
<img width="1436" height="832" alt="Screenshot 2025-09-16 at 3 35 27 pm" src="https://github.com/user-attachments/assets/93bbb4ff-b983-4b07-b942-89e25cd69f1d" />

### After completing and cleaning up your work, you can run terraform destroy. This command safely tears down all the infrastructure defined in your Terraform configuration. When executed, Terraform will first generate a plan showing which resources will be destroyed. It will then prompt you for confirmation—type yes to proceed. Once confirmed, Terraform deletes all the resources it had previously created, leaving your environment clean

<img width="1081" height="204" alt="Screenshot 2025-09-16 at 4 53 26 pm" src="https://github.com/user-attachments/assets/25e7bb5c-6ecf-4091-bc60-6eb38eee151d" />

<img width="1436" height="779" alt="Screenshot 2025-09-16 at 5 04 51 pm" src="https://github.com/user-attachments/assets/08639e1e-ef47-440c-bf9e-5037aec7da19" />


