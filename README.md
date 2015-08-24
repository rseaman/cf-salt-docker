# cf-salt-docker
Run infrastructure.json in CloudFormation.
Use generated resources as inputs to salt-master.json in CloudFormation.

Warning: Currently need to manually add a route to the VPC's default route table, '0.0.0.0/0' to the IGW.
