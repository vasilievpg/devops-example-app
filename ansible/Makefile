deploy:
	ansible-playbook release.yml -i inventory.yml --extra-vars="version=v5" -vv

setup:
	ansible-playbook setup.yml -i inventory.yml -vv --extra-vars "version=v4"