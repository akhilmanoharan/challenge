# challenge

I created a jenkins instance which is hosted in the AWS EC2. http://ec2-18-219-95-18.us-east-2.compute.amazonaws.com:8080/
Created a job to trigger the job and build the docker file.

To initiate connection on Pull Requests. I added github pull handler plugin to the jenkins and created a webook URL. [http://http://ec2-18-219-95-18.us-east-2.compute.amazonaws.com:8080/ghprbhook/]

The handshales are happening between the git and jenkins via the webhooks.

The permission in the webhook is set to trigger only on PR.

The images are getting added to image registry.


