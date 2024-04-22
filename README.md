# bedrock-cloud-init-hack

Update cloud-init to statically set cloud to AWS instead of attempting to read from /sys/devices/virtual/dmi

```curl -L https://raw.githubusercontent.com/jodydadescott/bedrock-cloud-init-hack/main/DataSourceEc2.py | sudo tee /usr/lib/python3.9/site-packages/cloudinit/sources/DataSourceEc2.py```
