

List the  objects from the s3 bucket 

$ansible-playbook s3_object_list.yaml --extra-vars "bucket_name=alb-zerp-beta-log aws_region=eu-north-1"

create new bucket in s3 

$ansible-playbook s3_bucket_creation.yaml --extra-vars "bucket_name=test-mani-devops aws_region=eu-north-1"

delete the bucket in s3 

$ansible-playbook s3_bucket_delete.yaml --extra-vars "bucket_name=test_mani_devops aws_region=eu-north-1"
