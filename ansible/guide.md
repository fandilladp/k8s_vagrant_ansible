# Flow 

`ansible-playbook -i hosts.ini preconfigure.yaml`

execute playbook, use directory
`ansible-playbook -i hosts.ini app.yaml`
configure-k8s
docker

## you add this file in all vm 
file in /script/prep.k8s.sh copy to your vm and execute 

``
- script manual -> execute in terminal
    sudo +x chmod ./prep.k8s.sh
    ./prep.k8s.sh
``

ansible playbook again 

`ansible-playbook -i hosts.ini app.yaml`

role 
kubernetes/master
kubernetes/node
