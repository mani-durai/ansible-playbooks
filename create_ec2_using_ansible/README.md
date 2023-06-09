 execution procedures :
 
 $ ansible-playbook ec2.yml --extra-vars "key_pair=<key_pair> aws_region=<region> group_id=<security_group_id> instance_type=<type> ami=<AMI Id> ins_name=<instance_name>  env=<Enviornemt>  vol_type=<volume_type> vol_size=<volume_size> subnet=<subnet_id>"


 example:

 key_pair : test (check key pair name in aws console )
 aws_region : us-east-1	
 group_id : sg-d9cc2faa
 instance_type : t3.micro or m5.xlarge
 ami : ami-ba602bc2
 env :  dev or uat or prod
 volume_type : gp2 or gp3 or io2   
 vol_size : 30 (GiB)
 subnet : subnet-0cb48f7a