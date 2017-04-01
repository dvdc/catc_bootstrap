# catc_bootstrap
for boostrapping cloud at cost nodes

## Running the playbook
`ansible-playbook -u root -k -K -i hosts -c ssh playbooks/global.yml`

## Supported Operating Systems
- Ubuntu

## Known Issues
Currently, the playbook will bomb halfway through, once you change the root password. You need to then re-auth with the new root pass. 
