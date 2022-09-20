deploy:
	ansible-playbook release.yml -i inventory.yml -vv --extra-vars "version=v4"

setup:
	ansible-playbook setup.yml -i inventory.yml -vv --extra-vars "version=v4"