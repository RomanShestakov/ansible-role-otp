# ansible-role-otp
Install erlang OTP from source

how to run a specific role locally
export ANSIBLE_ROLES_PATH=/path/to/role
ansible localhost --module-name include_role --args name=<role_name>

e.g
export ANSIBLE_ROLES_PATH=/home/romanshestakov/development;
sudo ansible localhost --module-name include_role --args name=ansible-role-otp

