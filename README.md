# linux-sample
Script:

    1  sudo service codedeploy-agent status
    2  sudo yum update
    3  sudo yum install ruby
    4  sudo yum install wget
    5  wget https://newcodedeploy.s3.us-east-1.amazonaws.com/latest/install     # Wrong Format since Bucket name is quite specific
    6  wget https://aws-codedeploy-us-east-1.s3.us-east-1.amazonaws.com/latest/install   # This is the correct format.[https://docs.aws.amazon.com/codedeploy/latest/userguide/resource-kit.html#resource-kit-bucket-names]
    7  chmod +x ./install
    8  sudo ./install auto
    9  sudo service codedeploy-agent status
   10  history


LINKS REGARDING CODEDEPLOY:
https://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-wordpress.html
https://docs.aws.amazon.com/codedeploy/latest/userguide/codedeploy-agent-operations-verify.html
https://docs.aws.amazon.com/codedeploy/latest/userguide/codedeploy-agent-operations-install-linux.html
