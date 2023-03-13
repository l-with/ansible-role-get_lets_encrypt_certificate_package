# Ansible Role Get Let's Encrypt Certificate Package

gets and installs Let's Encrypt certificate package from url

This role can be used to get a prepared package of a Let's Encrypt Cerificate (for instance by DNS challenge).

## Role Variables

### `get_lets_encrypt_certificate_package`

the configuration for the  Let`s Encrypt certificate package as dict with the items

- url_headers
- url
- secret
- le_domain
- le_domains
- notify
- group
- owner

### `get_lets_encrypt_certificate_package_url_headers`: `get_lets_encrypt_certificate_package.url_headers`

the headers for the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_url`: `get_lets_encrypt_certificate_package.url`

the url of the Let's Encrypt certificate package

### `get_lets_encrypt_certificate_package_secret`: `get_lets_encrypt_certificate_package.secret`

the secret to decrypt the certificate package

### `get_lets_encrypt_certificate_package_le_domain`: `get_lets_encrypt_certificate_package.le_domain`

the main domain of the certificate

### `get_lets_encrypt_certificate_package_le_domains`: `get_lets_encrypt_certificate_package.le_domains`

the string of domains for the certificate package

### `get_lets_encrypt_certificate_package_notify`: `get_lets_encrypt_certificate_package.notify`: 'get_lets_encrypt_certificate_package_noop_handler'

the handler to notify about changes

### `get_lets_encrypt_certificate_package_debug`: `get_lets_encrypt_certificate_package.owner`: `false`

if debug information should be printed

### `get_lets_encrypt_certificate_package_force`: `get_lets_encrypt_certificate_package.force`: `false`

if the certificate will be allways replaced
