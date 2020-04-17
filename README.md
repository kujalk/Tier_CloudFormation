# Tier_CloudFormation
Simple AWS CloudFormation template to create EC2 instances with appropriate security groups and Tags


Add image in your repository from upload file option then in README file

![alt text](data:image/jpeg;base64,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)
