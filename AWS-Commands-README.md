1. aws configure – Configure AWS CLI credentials

2. aws s3 ls – List S3 buckets

3. aws s3 cp file.txt s3://mybucket/ – Copy file to
S3

4. aws s3 sync . s3://mybucket/ – Sync local files
to S3

5. aws s3 rm s3://mybucket/file.txt – Delete file
from S3

6. aws ec2 describe-instances – List EC2 instances

7. aws ec2 start-instances --instance-ids
i-1234567890 – Start EC2 instance

8. aws ec2 stop-instances --instance-ids
i-1234567890 – Stop EC2 instance

9. aws ec2 terminate-instances --instance-ids
i-1234567890 – Terminate EC2 instance

10. aws ec2 create-key-pair --key-name MyKeyPair –
Create a new key pair

11. aws ec2 describe-volumes – List EBS volumes

12. aws ec2 create-volume --size 10 --region
us-east-1 – Create an EBS volume

13. aws ec2 attach-volume --volume-id vol-12345
--instance-id i-12345 --device /dev/sdf – Attach 
volume

14. aws ec2 describe-security-groups – List security
groups

15. aws lambda list-functions – List Lambda functions

16. aws lambda invoke --function-name my_lambda
output.json – Invoke a Lambda function

17. aws eks update-kubeconfig --name cluster_name –
Configure kubectl for EKS

18. aws rds describe-db-instances – List RDS
instances

19. aws rds stop-db-instance --db-instance-identifier
mydb – Stop RDS instance

20. aws rds start-db-instance
--db-instance-identifier mydb – Start RDS instance

21. aws ec2 create-snapshot --volume-id vol-12345 –
Create EBS snapshot

22. aws ec2 describe-snapshots – List EBS snapshots

23. aws cloudwatch describe-alarms – List CloudWatch
alarms

24. aws ssm send-command --document-name
AWS-RunShellScript --targets 
"Key=instanceIds,Values=i-12345" --parameters
commands="df -h" – Run command on EC2

25. aws iam list-users – List IAM users

26. aws iam list-roles – List IAM roles

27. aws route53 list-hosted-zones – List Route 53
hosted zones

28. aws route53 create-hosted-zone --name example.com
– Create a Route 53 hosted zone

29. aws cloudformation list-stacks – List
CloudFormation stacks

30. aws cloudformation create-stack --stack-name
my-stack --template-body file://template.json –
Create a stack

31. aws cloudformation delete-stack --stack-name
my-stack – Delete a stack

32. aws ecr get-login-password --region us-east-1 |
docker login --username AWS --password-stdin 
account_id.dkr.ecr.us-east-1.amazonaws.com –
Login to ECR

33. aws ecr create-repository --repository-name
myrepo – Create an ECR repository

34. aws ecr list-repositories – List ECR repositories

35. aws dynamodb list-tables – List DynamoDB tables

36. aws dynamodb describe-table --table-name mytable
– Describe a DynamoDB table

37. aws dynamodb put-item --table-name mytable --item
'{"id": {"S": "123"}, "name": {"S": "Test"}}' –
Insert item into DynamoDB

38. aws sns list-topics – List SNS topics

39. aws sns publish --topic-arn 
arn:aws:sns:us-east-1:123456789012:MyTopic
--message "Hello" – Send SNS message

40. aws sqs list-queues – List SQS queues

41. aws sqs send-message --queue-url
https://sqs.us-east-1.amazonaws.com/123456789012/My 
Queue --message-body "Test message" – Send message 
to SQS

42. aws sqs receive-message --queue-url 
https://sqs.us-east-1.amazonaws.com/123456789012/My
Queue – Receive SQS message

43. aws kms list-keys – List KMS keys

44. aws kms encrypt --key-id key-id --plaintext
"Hello" – Encrypt text using KMS

45. aws kms decrypt --ciphertext-blob 
fileb://encrypted.txt – Decrypt KMS ciphertext

46. aws ec2 describe-key-pairs – List EC2 key pairs

47. aws ec2 delete-key-pair --key-name MyKeyPair –
Delete a key pair

48. aws s3 mb s3://my-new-bucket – Create a new S3
bucket

49. aws s3 rb s3://my-new-bucket --force – Delete an
S3 bucket

50. aws cloudfront list-distributions – List
CloudFront distributions
