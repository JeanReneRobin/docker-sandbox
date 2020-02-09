# ansible-nodes
A shell script used to deploy and manage local docker containers.

```shell
ansible-nodes
    
Description:
  A shell script used to deploy and manage local docker containers and network.
    
Usage:
  ./ansible-nodes [command] [options]
    
Available Commands:
  help        		Dispaly this message
  pop [n] [i]      	Deploy n containers using i image. 25 nodes maximum. 
  download    		Download dockers images
  delete      		Delete containers
  stop        		Exit and clean existing environnement
```

### Credits
https://github.com/Nani-o/ansible101
