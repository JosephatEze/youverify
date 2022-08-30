NOTE:
1. The CI/CD tool used for this project is circleCi and its configuration is located at .circleci folder

2. The kubernetes cluster is provisioned with terraform and the automation code is at Terraform folder

3. The kubernetes deployments is at k8s folder

4. The dockerfile is at the folder of each service

5. The CI/CD environment variables which includes the aws authentication details (IAM user secreet and access key) should be stored in the circleci environment variables

6. The AWS IAM user should have kubernetes permission
