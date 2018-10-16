# Kibana packer

This is the folder used to do AMI in AWS.

1) create repo, and initialise it on github as well,
2) do berkfile manually,
```source 'https://supermarket.chef.io'

cookbook 'kibana', git: 'https://github.com/oceaneLonneux/kibanaCookbook'
```
3) create the packer.json file and fill it with the right configuration.
