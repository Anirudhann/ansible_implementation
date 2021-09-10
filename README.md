# ansible_implementation
Describes how we can utilize ansible and achieve Continuous Deployment (CD)

# To run this ansible playbook - please use the below command
## Note: Only for first time - server dependencies need to be installed
## 1. first time server_setup=True, then False or dont give that params
## 2. git_tag=tag/branch name, else it will take default branch given in code
ansible-playbook ansible/deployment/deploy.yml -K -e'server_setup=True git_tag=master'

