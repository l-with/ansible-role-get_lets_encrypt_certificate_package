# Ansible Role Get Let's Encrypt Certificate Package

gets and installs Let's Encrypt certificate package from url

This role can be used to get a prepared package of a Let's Encrypt Cerificate (for instance by DNS challenge).

## Role Variables

### `get_lets_encrypt_certificate_package_url_headers`

the headers for the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_url`

the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_secret`

the secret to decrypt the certificate package

### `get_lets_encrypt_certificate_package_FQDN`

the FQDN of the certificate

### `get_lets_encrypt_certificate_package_notify`

the handler to notify about changes
