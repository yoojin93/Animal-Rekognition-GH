Created 2 datasets, 1 with 100+ dog photos, and the other with 100+ cat photos to train the Rekognition model. Labeled each image either "Cat" or "Dog" according to the type of animal they are in the photo. Used Session Manager in the EC2 instance created from the CloudFormation template to create a Docker image and push it into an ECR repository. Created an ECS cluster, Task definitions, and a Service. 
