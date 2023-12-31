# EC2_Instance_using_AWS_CFT

Cloud formation template used to automate the provisioning of resources, manage stacks, and ensure consistent infrastructure across deployments and also helps in detecting the resource if they were accidently or intentionally deleted

In this project, created an EC2 instance using AWS CFT and deleted its EC2 instance with the help of drift detection we identified that EC2 instance have been deleted

Written a code formation template in YAML or JSON

Code in YAML:

![Alt text](CFT_code_YAML.png)

Code in JSON:

![Alt text](CFT_code_JSON.png)

Create a stack in AWS CFT services

![Alt text](Stack_creation.png)

Stack have been created and CFT template helped to create stack

With the help of stack an EC2 instance have been created using cloud formation template

![Alt text](Initiated_instance_using_stack.png)

Instance ID will be same as EC2 instance ID

![Alt text](Stack_Instance_ID.png)

EC2 instance as well as stack created instance ID matching

![Alt text](EC2_Instance.png)

After deleting its EC2 instance drift have been detected

![Alt text](Drift_detected.png)

