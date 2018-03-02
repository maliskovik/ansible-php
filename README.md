# Php ansible role
Installs php with dependencies.

## Optional variables
* php_version - php version to install
* php_repo - php repository to use.
* php_packages - main php packages to use.
* php_packages_custom - Optional packages to use - change this
* php_config_lines - config lines to modify in php config ( list)
  * key - key to look for
  * value - value of the key
