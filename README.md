# Auto-Restart-EXSi

- restart if use Macmini : 

pmset autorestart 1

- Restart VM on ESXi
+ Enable auto restart on manage host 
+ Enable auto restart each VMs which VM you wants autorestart.

![Screen Shot 2021-11-24 at 13 45 22](https://user-images.githubusercontent.com/64687828/143188997-e34d58b3-cfd4-4e07-b53c-b9a6de6bb649.png)


![Screen Shot 2021-11-24 at 13 45 01](https://user-images.githubusercontent.com/64687828/143189032-da55c5a1-aa61-4062-b2c1-b8ed2bb21937.png)



optional: Case : Cannot complete login due to an incorrect user name or password

- ssh to ESXI to restart managemnet agent :
+ for ESXi host :    /etc/init.d/hostd restart

+ for vencenter host: /etc/init.d/vpxa restart

Detail : https://kb.vmware.com/s/article/1003490


