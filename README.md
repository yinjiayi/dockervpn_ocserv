# dockervpn_ocserv
curl https://get.docker.com | sh  
systemctl start docker  
systemctl enable docker  
docker run --privileged -p 443:443 -p 443:443/udp -d yinjiayi/ocserv_askycn_com
