# 

* example 
```
ansible-playbook -i hosts.yml all.yml --extra-vars '{"kafkabroker_install": true, "zookeeper_install": false}'

```


## Reference

* [cp-ansible](https://github.com/confluentinc/cp-ansible)
* [Running Kafka in Production](https://docs.confluent.io/current/kafka/deployment.html#cp-production-parameters)