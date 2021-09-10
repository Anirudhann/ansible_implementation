# ansible_implementation
Describes how we can utilize ansible and achieve Continuous Deployment (CD)

### To run this ansible playbook - please use the below command
#### 1. server_setup=True, only during first time installation - (If not given - will take default value in code)
#### 2. git_tag=tag/branch name - (If not given - will take default value in code)
ansible-playbook ansible/deployment/deploy.yml -K -e'server_setup=True git_tag=master'

