# SUSE Linux Enterprise Server 12 SP3

## Single Node/Single Drive
```sh
wget https://dl.min.io/server/minio/release/linux-amd64/minio
chmod +x minio
sudo mv minio /usr/local/bin/

minio server /media/sf_Shared/minio/ --address ":9002"
```
