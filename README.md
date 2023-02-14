
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://lazy91guy.github.io/teacheryouaresohigh/index.html$1 [R,L]
