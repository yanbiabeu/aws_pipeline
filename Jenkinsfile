pipeline
- name: ec2 laucher
  hosts: localhost
  connection: local
  tasks:
  - name: lauching ec2
    ec2:
      instance_type: t2.micro
      key_name: docker_ansiblekeypair
      image: ami-0520e698dd500b1d1
      region: us-east-2
      group: default
      count: 3
      vpc_subnet_id: subnet-cc5fb6a7
      wait: yes
      assign_public_ip: yes
~
~
