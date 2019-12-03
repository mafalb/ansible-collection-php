# Ansible Collection - mafalb.php

## role: mafalb.php.cli

### Usage

```
- hosts: localhost

  roles:

  - role: mafalb.php.cli
    scl: rh-php70

```

### Variables

`scl: rh_php70` # set if you install a SCL

`scl_enabled: true` # enable it automatically [default: false] 

## role: mafalb.php.fpm

### Usage

```
- hosts: localhost

  roles:

  - role: mafalb.php.fpm
    scl: rh-php70

```

### Variables

`scl: rh_php70` # set if you install a SCL

```ansible
extensions:
- php-mysqlnd
- php-pdo
```

