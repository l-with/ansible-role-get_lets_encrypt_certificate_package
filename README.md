# Ansible Role GitLab Let's Encrypt

Gets and installs Let's Encrypt certificate from GitLab project

## Role Variables

### `gitlab_lets_encrypt_api_token`

the private token for fetching the certifcate package

### `gitlab_lets_encrypt_package_url`

the url of the Let's Encrypt certificate package

### `gitlab_lets_encrypt_notify`

the handler to notify about changes
