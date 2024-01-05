# ansible_fortimanager

Here are all Ansible Playbooks related to FortiManager. In order for the Playbooks to be executed successfully, the admin user must have the "read-write" RPC permit.

```
config system admin user
    edit "your_admin_user"
        set rpc-permit read-write
    next
end
```