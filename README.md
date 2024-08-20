# github-aws-self-hosted

# demo of self hosted and github hosted runner

steps:
# first need to create the githhub repository and place the yml file 
# the yml file directory structure should be .github/workflows  inside this folder we need to place yml file(runner file)

# for self hosted runner need to specify as self-hosted in runs-on command for github hosted we can specify any like ubuntu-latest etc..

# steps for self hosted : go to settings of the repository 
# actions -> runner -> click on self hosted runner and flow the steps 
# in aws create the ec2 instance with inbound and outbound traffic allowed with http,https in security tab
