# CICD_TP_Build_AMI

## Prerequisites
  - Jenkins + Config pipeline
  - Persistent Iptables & Iptable to redirect 80 -> 8080
  - JQ
  - AWS CLI for next steps
 
 
 # Bugs
Pipeline multibranch Jenkins doesn't preload parameters on Jenkinsfile before it started a first time. 
Every time parameters are changed in Jenkinsfile, you need to start and stop the pipeline to update params in Jenkins UI.
  - https://issues.jenkins-ci.org/browse/JENKINS-40574
  - https://issues.jenkins-ci.org/browse/JENKINS-41929
