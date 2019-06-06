Cloudflare Firewall Rules Preset or bot request blocker.

```
(http.request.uri.path eq "/wp-login.php") or 
(http.request.uri.path eq "/xmlrpc.php") or 
(http.request.uri.path eq "/administrator/index.php") or 
(http.request.uri.path eq "/admin") or 
(http.request.uri.path eq "/news/wp-login.php") or 
(http.request.uri.path eq "/admin.php") or 
(http.request.uri.path eq "/site/wp-login.php") or 
(http.request.uri.path eq "/forum/wp-login.php") or 
(http.request.uri.path eq "/wp/wp-login.php") or
(http.request.uri.path eq "/1/wp-login.php") or
(http.request.uri.path eq "/shop/wp-login.php") or
(http.request.uri.path eq "/blog/wp-login.php") or
(http.request.uri.path eq "/administrator/") or
(http.request.uri.path eq "/wp-admin/") or
(http.request.uri.path eq "/index.php?option=com_jce&task=plugin&plugin=imgmanager&file=imgmanager&method=form") or
(http.request.uri.path eq "/components/com_jbcatalog/libraries/jsupload/server/php") or
(http.request.uri.path eq "/user/login") or
(http.request.uri.path eq "/cgi-bin/config.exp") or
(http.request.uri.path eq "/forums/wp-login.php") or
(http.request.uri.path eq "/admin/wp-login.php") or
(http.request.uri.path eq "/new/wp-login.php") or
(http.request.uri.path eq "/.vscode/sftp.json") or
(http.request.uri.path eq "/.remote-sync.json") or
(http.request.uri.path eq "/.ftpconfig") or
(http.request.uri.path eq "/.vscode/ftp-sync.json") or
(http.request.uri.path eq "/deployment-config.json") or
(http.request.uri.path eq "/domain/wp-login.php") or
(http.request.uri.path eq "/portal/wp-login.php") or
(http.request.uri.path eq "/administrator/components/com_rokdownloads/assets/uploadhandler.php") or
(http.request.uri.path eq "/administrator/components/com_extplorer/uploadhandler.php") or
(http.request.uri.path eq "/portal/wp-login.php") or
(http.request.uri.path eq "/index.php?option=com_jdownloads&Itemid=0&view=upload") or
(http.request.uri.path eq "/components/com_facileforms/libraries/jquery/uploadify.php") or
(http.request.uri.path eq "/index.php?option=com_adsmanager&task=upload&tmpl=component") or
(http.request.uri.path eq "/politic/wp-login.php") or
(http.request.uri.path eq "/sftp-config.json") or
(http.request.uri.path eq "/" and http.request.method eq "POST") or (http.request.uri contains ".git/" and http.request.method in {"GET" "POST" "HEAD" "OPTIONS"})
```
