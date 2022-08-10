[defaults]
inventory = ./inventory
#connect_timeout = 60
#remote_user = vagrant
ask_pass = true
#host_key_checking = false
log_path=/home/ansible/log/ansible_out.log

[privilege_escalation]
become = true
become_method = sudo
become_user = root
become_ask_pass = true

## To address -> "Shared connection to serverb closed" ##
#ansible_python_interpreter = /usr/bin/python2.7
#ansible_python_interpreter = /usr/bin/python3


====================
[hlist]
rfernando-test.bo3.e-dialog.com
#rfernando-test1.bo3.e-dialog.com

#[weblist]
#servera #192.168.56.101
#serverb #192.168.56.103

#[applist]
#app0[1:2]

#[dblist]
#db01 #192.168.56.102

