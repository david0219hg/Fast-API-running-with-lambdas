# This project runs in fastAPI and it has iac in SAM

-- for running the project locally run it like a fastapi project but for running it on AWS you need to create a folder called 
my_layer and inside it create a folder called python then install all the libraries of the requirements there.

for uploading it to the cloud you need aws cli and sam cli configured, then you need to run sam build and 
sam deploy --stack-name fast-api-stack2 --s3-bucket fast-api-project --capabilities CAPABILITY_IAM
