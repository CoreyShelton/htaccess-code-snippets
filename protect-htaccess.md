# Protect The .htaccess File

The following code snippet protects the .htaccess file itself

***

```
##############################
# Protect the .htaccess file #
##############################
<files .htaccess>
order allow,deny
deny from all
</files>
```
