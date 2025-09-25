# ansible-automation

### Execute below command to configure master node
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i inventory/k8s-nodes/aws_ec2.yaml master-playbook.yml

### Execute below command to configure worker node
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i inventory/k8s-nodes/aws_ec2.yaml worker-playbook.yml