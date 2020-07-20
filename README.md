# shared-settings


# Ansible

Run playbook without extra vars

``` ansible-playbook ```

Run playbook with un-encrypted vars

``` ansible-playbook [PATH_TO_PLAYBOOK] --extra-vars="@[PATH_TO_VARS]" ```

Run playbook with encrypted vars (If run within mysql-directory)

``` ansible-playbook [PATH_TO_PLAYBOOK] --extra-vars="@[PATH_TO_VARS]" ```

Run playbook with encrypted vars (If run from anywhere)

``` ansible-playbook [PATH_TO_PLAYBOOK] --extra-vars="@[PATH_TO_VARS_FILE]" --ask-vault-pass ```
