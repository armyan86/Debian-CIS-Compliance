# Debian-CIS-Compliance
I collect configurations for GNU\Linux Debian OS in accordance with CIS standards

#Run the following command and verify Uid and Gid are both 0/root and Access does not grant permissions to group or other:
stat /etc/ssh/sshd_config
Access: (0600/-rw-------)  Uid: (    0/    root)   Gid: (    0/    root)
