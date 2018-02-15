# LDAP client
This ansible role configures the client to  authenticate users via LDAP.

## Optional variables
* ldap_client_host: address of the ldap server
* ldap_client_port: Port on which LDAP server listens
* ldap_client_dn: base DN to use for users
* ldap_client_version
* ldap_client_ssl: on or off
* ldap_client_cacertdir: Where certificate file is located ( for ssl)
* ldap_client_config_file: Location of the ldap config on client (just leave default)
* ldap_client_create_user_home_on_login: Whether to create user home dir on first login
* ldap_client_default_user_umask: Umask to use. Default to 077(owner only permissions), could also be set to 022 to allow others and group to read user files.
* ldap_client_optional_packages: Additional packages to install
