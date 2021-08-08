# Ansible Role Get Let's Encrypt Certificate Package

gets and installs Let's Encrypt certificate package from url

This role can be used to get a prepared package of a Let's Encrypt Cerificate (for instance by DNS challenge).

## Role Variables

### `get_lets_encrypt_certificate_package`

the configuration for the  Let`s Encrypt certificate package as dict with the items

- url_headers
- url
- secret
- FQDN
- notify

### `get_lets_encrypt_certificate_package_url_headers`: `get_lets_encrypt_certificate_package.url_headers`

the headers for the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_url`: `get_lets_encrypt_certificate_package.url`

the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_secret`: `get_lets_encrypt_certificate_package.secret`

the secret to decrypt the certificate package

### `get_lets_encrypt_certificate_package_FQDN`: `get_lets_encrypt_certificate_package.FQDN`

the FQDN of the certificate

### `get_lets_encrypt_certificate_package_notify`: `get_lets_encrypt_certificate_package.notify`

the handler to notify about changes
