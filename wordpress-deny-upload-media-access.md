# Wordpress Specific

####Only users who are logged in can access the */wp-content/uploads/* images and files**

```Text
<IfModule mod_rewrite.c>
RewriteCond %{REQUEST_FILENAME} -s
RewriteRule ^wp-content/uploads/(.*)$ dl-file.php?file=$1 [QSA,L]
</IfModule>
```
