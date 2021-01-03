This is a playground for various ansible playbooks to help manage an OctoPrint based 3D Print Farm


Configure inventory.yml to define your hosts 

Run deployment on test host group only
`ansible-playbook --limit test up.yml --verbose`

