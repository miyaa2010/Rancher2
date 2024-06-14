# rancher2 cài rancher trên node worker1
su - sysadmin

docker run --name rancher-server -d --restart=unless-stopped -p 6860:80 -p 6868:443 --privileged rancher/rancher:v2.5.7 

Tiếp theo chọn vào Add Cluster --> Other Cluster --> Nhập Cluster Name --> Chọn Create.
