## to build vault
ansible-vault encrypt --encrypt-vault-id=default -J group_vars/all.yml.old -vvvvvv --output group_vars/all.yml

#### je sais que all.yml.old ne doit pas etre dans le push mais comment vous allez verifier sinon ?