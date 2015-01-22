#cluster-playbooks

NB scripts should be providing with the target host group either 
via the command line or from a calling script, e.g.

    ansible-playbook  aoflagger-deps.yml  --extra-vars "target=localhost" -K
