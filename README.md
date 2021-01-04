This is a playground for various ansible playbooks to help manage an OctoPrint based 3D Print Farm

Start with a fresh RaspiOS SD image (currently testing against armf builds only)

Configure inventory.yml to define your hosts 
    - Hosts - All your hosts managed by this playbook
    - Children - Subgroups for role assignment ie Test/Production

Copy SSH keys to the remote hosts for ansbile to have access
`sh-copy-id pi@<ip.address>`

Run deployment on test host group only
`ansible-playbook --limit test up.yml --verbose`

