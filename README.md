# ansible-coolworld
coolworld ansible




## Setup/Installation

    ansible-galaxy install --roles-path=./roles --role-file=./requirements.yml
    ansible-playbook -i ~/.ansible-inventory --vault-password-file ~/.ansible-vault-password ./main.yml
