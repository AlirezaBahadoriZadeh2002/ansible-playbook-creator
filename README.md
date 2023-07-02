# ansible-playbook-creator
- Run format 1:

      ansible-playbook -i inventory/hosts myproject.yaml --extra-vars "name={project_name}"

- Run format 2:

      ansible-playbook -i inventory/hosts myproject.yaml 

And answer to the question:

      Enter the name project:
