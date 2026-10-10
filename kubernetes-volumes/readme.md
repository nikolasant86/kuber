# скопировал все файлы из предыдущей ветки
# создал файл cm.yaml
# создал файл pvc.yaml
# создал nfs хранилище на отдельном сервере
# установил в кластер NFS CSI driver, version: v4.13.4 
    'curl -skSL https://raw.githubusercontent.com/kubernetes-csi/csi-driver-nfs/v4.13.4/deploy/install-driver.sh | bash -s v4.13.4 --'
# создал файл storageClass.yaml
# модифицировал pvc.yaml, удовлетворяющий storageClass.yaml
# модифицировал манифесты nginx-pod-configmap.yaml deployment.yaml ingress.yaml