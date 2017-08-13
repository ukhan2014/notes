How to mount AWS instance home directory on local machine over SSHFS:
sshfs -o "IdentityFile=/path/to/identity-file.pem" username@aws.instance.com:/home/ubuntu/ /mnt/point/on/local/machine/

