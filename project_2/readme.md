:fire: **ANSIBLE!** :star2:

# setuping for the ansible
* Step by step
   * setup.txt  - to do list for ansible vm
   * ansible 
   
| Description | command |
| --- | --- |
| Ping all deivce per required |  ansible -m ping all -i hosts |

```bash 
ansible -m pi ng all -i hosts  
``` 




Des | command |
| --- | --- |
| Lising a inventory list in your host | ansible-inventory --list |

```bash 
ansible-inventory --list  
``` 

Des | command |
| --- | --- |
| Play ansible playbook, SSH password has been entered in  "var/group_var |  ansible-playbook playb.yml |

```bash
ansible-playbook playb.yml
```

  Playbook  |  Description  |
|  --- |  ---  |
|  [playb.yml](/Py-sho-ver-onbox)  |  show ip interefaces for switches and routers. |
|  [playb2.yml ](/tdr-test)  |  enable CDP on both routers and switches.  |
|  [playb3.yml ](/eem_configdiff_to_spark)  |  playb3.yml  enable OSPF on routers.  |
