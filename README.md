# jenkins_docker_build
This dockerfile is pickedup at each commit by jenkins via a payload delivered via github webhook
Jenkins server is running on an aws ec2 instance.
Jenkins would clone this repositary and then trigger an inage build
post image build jenkins would run the container
Final effect is "BRK is the captain" webpage is displaced by the apache server running on the container. 

All of this is on Amazon EC2 instance. 
