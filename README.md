## OIDC with ldap user backend
##### credit for the IODC library [jumbojett](https://github.com/jumbojett/OpenID-Connect-PHP)
just put the files into the middleware folder and change the config.php to LdapAuthMiddleware.php and rename the original to LdapAuthMiddleware.php.old
finally change the variables in OIDC-LDAP.php to match your OIDC provider.
*note currently the redirect url is automatically changed to https vs http scheme so beware of that*
__This is still very much a work in progress but it,s better than nothing if anybody wants to make even trivial changes please make a pull request unless it's way off point it should be accepted__
