experiments
===========

```console
satnam@kubernetes-minion-1:~$ sudo -s
root@kubernetes-minion-1:/home/satnam# docker ps
CONTAINER ID        IMAGE                                     COMMAND                CREATED             STATUS              PORTS                    NAMES
a309846b005c        ubuntu:14.04                              "\"bash -c 'i=\"0\";   3 days ago          Up 3 days                                    k8s_synth-lgr.ede24f12_synthetic-logger-10lps-pod.default.etcd_35c7b808-6c45-11e4-a194-42010af05d02_2abc4cd9                                
d8d60784806b        kubernetes/pause:latest                   "/pause"               3 days ago          Up 3 days                                    k8s_net.dbcb7509_synthetic-logger-10lps-pod.default.etcd_35c7b808-6c45-11e4-a194-42010af05d02_be1026dd                                      
2f47a6219e82        kubernetes/heapster:0.2                   "/run.sh /bin/bash"    3 days ago          Up 3 days                                    k8s_heapster.24e32151_heapster.default.etcd_511e5a9d-6c39-11e4-a194-42010af05d02_b5ed97c1                                                   
7dfd030bab93        kubernetes/fluentd-elasticsearch:latest   "/run.sh"              3 days ago          Up 3 days                                    k8s_fluentd-es.f0eebcdc_fluentdesmanife2u464h05heqcpotoddodpnehjaqsde.default.file_fluentdesmanife2u464h05heqcpotoddodpnehjaqsde_90bbba27   
9a869d00c17b        ubuntu:14.04                              "\"bash -c 'i=\"0\";   3 days ago          Up 3 days                                    k8s_synth-lgr.f0d3e2b_synthetic-logger-0.25lps-pod.default.etcd_7c7d3b8d-6c39-11e4-a194-42010af05d02_d3c519d5                               
6abc80cadf3f        kubernetes/pause:latest                   "/pause"               3 days ago          Up 3 days                                    k8s_net.dbcb7509_synthetic-logger-0.25lps-pod.default.etcd_7c7d3b8d-6c39-11e4-a194-42010af05d02_a8e3b763                                    
9b2787803043        kubernetes/pause:latest                   "/pause"               3 days ago          Up 3 days                                    k8s_net.dbcb7509_heapster.default.etcd_511e5a9d-6c39-11e4-a194-42010af05d02_f3fac3cc                                                        
fda05d821371        kubernetes/pause:latest                   "/pause"               3 days ago          Up 3 days                                    k8s_net.dbcb7509_fluentdesmanife2u464h05heqcpotoddodpnehjaqsde.default.file_fluentdesmanife2u464h05heqcpotoddodpnehjaqsde_936da1a7          
04b1225d0ed3        google/cadvisor:0.5.0                     "/usr/bin/cadvisor"    3 days ago          Up 3 days                                    k8s_cadvisor.b0dae998_cadvisormanifes12uqn2ohido76855gdecd9roadm7l0.default.file_cadvisormanifes12uqn2ohido76855gdecd9roadm7l0_70af8640     
ecf63dd4aa43        kubernetes/pause:latest                   "/pause"               3 days ago          Up 3 days           0.0.0.0:4194->8080/tcp   k8s_net.a0f18f6e_cadvisormanifes12uqn2ohido76855gdecd9roadm7l0.default.file_cadvisormanifes12uqn2ohido76855gdecd9roadm7l0_9e43beba          
```
