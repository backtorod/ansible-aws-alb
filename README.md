# ansible-aws-alb


```shell
$ ansible-galaxy install \
    -r requirements.yml \
    -p roles \
    --force
```

```shell
ansible-playbook main.yml \
    -e survey_aws_profile=terraform-cloud44
```