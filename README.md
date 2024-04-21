# subject-220421

## FileZilla Client
  - [FTP、FTPS、SFTPのクライアント

  ![image](https://github.com/winofsql/subject-220421/assets/1501327/e348025f-0c8f-47f5-967d-15ee8c9cadd2)
    
  ![image](https://user-images.githubusercontent.com/1501327/164434092-35ea584f-dc73-4211-b4e4-b5638b857ee0.png)\
  ![image](https://winofsql.jp/image/a/filezilla-install-settings-2.png)\
  ![image](https://winofsql.jp/image/a/filezilla-install-settings-3.png)

## .htaccess
```
DirectoryIndex index.php
Options +Indexes
DirectoryIndex /index/files.php

RewriteEngine on
RewriteCond %{HTTPS} off
RewriteRule ^(.*)$ https://%{HTTP_HOST}%{REQUEST_URI} [R=301,L]
RewriteCond %{HTTP_HOST} ^www\.(.*) [NC]
RewriteRule ^ http://%1%{REQUEST_URI} [L,R=301]
```

