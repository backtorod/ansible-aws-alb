# ansible-aws-alb


```shell
$ ansible-galaxy install \
    -r requirements.yml \
    -p roles \
    --force
```

```shell
$ ansible-playbook main.yml \
    -e survey_aws_access_key_id=${AWS_ACCESS_KEY_ID} \
    -e survey_aws_secret_access_key=${AWS_SECRET_ACCESS_KEY} \
    -e survey_aws_region=us-east-1
```