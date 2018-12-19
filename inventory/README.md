## Overview

- setup EC2

### How to setup

```
$ wget https://raw.githubusercontent.com/ansible/ansible/devel/contrib/inventory/ec2.ini
$ wget https://raw.githubusercontent.com/ansible/ansible/devel/contrib/inventory/ec2.py
```

1. Create `ec2.ini`

```ec2.ini
# Ansible EC2 external inventory script settings

;[credentials]
;aws_access_key_id =
;aws_secret_access_key =
;regions = us-east-2

[ec2]
elasticache = False
cache_max_age = 300
```