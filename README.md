# ansible-role-otp
Install erlang OTP from source

how to run a specific role locally
export ANSIBLE_ROLES_PATH=/path/to/role
ansible localhost --module-name include_role --args name=<role_name>

e.g
export ANSIBLE_ROLES_PATH=/home/romanshestakov/development;

cd $ANSIBLE_ROLES_PATH
sudo ansible localhost --module-name include_role --args name=ansible-role-otp

to install prerequisite dependencies libwxgtk use ansible-role-wxWidgets
