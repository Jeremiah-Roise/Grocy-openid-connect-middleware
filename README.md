## OIDC with ldap user backend
##### credit for the IODC library [jumbojett](https://github.com/jumbojett/OpenID-Connect-PHP)
just put the files into the middleware folder and change the config.php middleware name to IODC-LDAP.
finally change the variables in OIDC-LDAP.php to match your OIDC provider.
*note currently the redirect url is automatically changed to https vs http scheme so beware of that*