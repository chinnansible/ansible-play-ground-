# Interactive Katacoda Scenarios

yum install -y git && git clone https://github.com/irixjp/katacoda-scenarios && cd katacoda-scenarios/master-course-data/assets/tools/

bash ./kata_setup.sh

Ansible version is below:

ansible --version

ansible.cfg is below:

cat ~/.ansible.cfg

Inventory file is below:

cat ~/inventory


There are some related commands.

ansible-lint --version

yamllint --version

git --version

Sample commands:

ansible all --list-hosts

ansible web -m ping

ansible node-1 -m shell -a 'hostname'



[![](http://shields.katacoda.com/katacoda/irixjp/count.svg)](https://www.katacoda.com/irixjp "Get your profile on Katacoda.com")

Visit https://www.katacoda.com/irixjp to view the profile and interactive scenarios

### Writing Scenarios
Visit https://www.katacoda.com/docs to learn more about creating Katacoda scenarios

For examples, visit https://github.com/katacoda/scenario-example
