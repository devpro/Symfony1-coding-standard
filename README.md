Symfony1 PHP CodeSniffer Coding Standard
========================================

A code standard to check against the Symfony 1 coding standards.
Initially copied from [phpcs-symfony](https://github.com/willdurand/phpcs-symfony).

Installation
------------

1. Install phpcs:

        pear install PHP_CodeSniffer

2. Find your PEAR directory:

        pear config-show | grep php_dir

3. Copy, symlink or check out this repo to a folder called Symfony inside the
   phpcs `Standards` directory:

        cd /path/to/pear/PHP/CodeSniffer/Standards
        git clone git://github.com/devpro/Symfony-coding-standard.git Symfony

4. Use Symfony as coding standard:

        phpcs --config-set default_standard Symfony2
