# Scenario
Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.

You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.

This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

# How to run?
change current directory to cloudformation-iac/commands. and run
<ul>
<li>./create.sh network-infra-stack network-infra.yml network-infra.json</li>
<li>./create.sh server-stack server.yml server.json</li>
</ul>

# Prerequisites
Scripts assume that there is an s3 bucket with name <b>udagram-webapp</b> and webapp.zip folder exists. webapp.zip is available in /resources
