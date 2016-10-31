# ansible-aws-asg

Calling Ansible playbook in user data for AWS Auto Scaling Launch Configuration

Requirements
````
- S3 bucket for storing the Ansible Playbook zip file
- Instance profile role for the launched instance with access to S3
- S3 bucket with appropiate permissions
````
