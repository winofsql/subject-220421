# subject-220421

## FileZilla Client
  - [FTP、FTPS、SFTPのクライアント\
![image](https://user-images.githubusercontent.com/1501327/157356406-cb368674-ea88-4d66-8bd7-e95b2e120197.png)](https://filezilla-project.org/download.php?show_all=1)\
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

## ロリポップ Python バージョン
![image](https://user-images.githubusercontent.com/1501327/164386514-e96deace-d0c8-40a3-b1fb-2581920508ee.png)
