# Ensure boto is installed either through rpm or pip
python2-botocore-1.6.0-1.el7.noarch

python2-boto3-1.4.6-1.el7.noarch

python2-boto-2.45.0-3.el7.noarch


# To create the instances first export the following
AWS_SECRET_ACCESS_KEY=g/8PmDNYHVSSFDDFSDFSFDFDFSDFSFSSFFbWQpjH
AWS_ACCESS_KEY_ID=BKIRSAFETYDANCE


# To terminate instances
ansible-playbook -i ec2.py terminate.yaml 

