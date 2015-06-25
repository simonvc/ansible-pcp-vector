# ansible-pcp-vector
Two very simple playbooks to install performance co-pilot and netflix Vector onto Ubuntu 14.04
Based on https://www.djouxtech.net/posts/install-vector-with-ansible/

1/ Create a ansible_hosts file that looks like this:

```
[pcphosts]
host1
host2

[vectorhosts]
host1
```

2/ run the playbooks

```
ansible-playbook -i ansible_hosts pcp.yml
```

```
ansible-playbook -i ansible_hosts vector.yml
```

3/ Open the vector host dashboard htt://host1:3000/




