# raspberries
Input to Flux for NFS Provisioner

bob@linuxworkstation:~/github/kubernetes-sigs/nfs-subdir-external-provisioner/deploy/helm$ helm template nfs-subdir-external-provisioner . --set nfs.server=192.168.2.3 --set nfs.path=/mnt/zNAS/k3s --namespace nfs --output-dir .

