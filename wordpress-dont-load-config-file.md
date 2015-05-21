# Wordpress Don't Load wp-config.php

The following code snippet prevents wp-config.php from loading

```
#####################################
# Don't Allow wp-config.php To Load #
#####################################
<Files wp-config.php>
order allow,deny
deny from all
</Files>
```
