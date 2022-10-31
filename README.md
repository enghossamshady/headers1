# headers1
this is the headers of vmware in linux debain 11 


sudo git clone \              
  -b workstation-$( grep player.product.version /etc/vmware/config | sed '/.*\"\(.*\)\".*/ s//\1/g' ) \
  https://github.com/mkubecek/vmware-host-modules.git \
  /opt/vmware-host-modules/
