Node_CustomPlatform_AmazonLinux
===============================
This repository contains the source for an Elastic Beanstalk Custom Platform.
This custom platform is based on **Amazon Linux 2018.03.0** and supports **Node.js 12.14.0**.

See the Packer template, *custom_platform.json*, for details on the AMI and
scripts that the builder runs as it creates the custom platform.

Once Packer has built the custom platform, it is available in the Console,
EB CLI, and APIs/SDKs as "Sample NodeJs Container".

For further information on custom platforms, see the
[Custom Platforms docs](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/custom-platforms.html).

Start a Micro machine in the same region and account with the EBS and SSH into it.
Install EB CLI

```
pip install --upgrade --user awsebcli

export PATH=$PATH:$HOME/.local/bin

git clone https://...this sameple app.

```

