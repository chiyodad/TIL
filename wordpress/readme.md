# 외부 URL 호출 (curl 대신 사용)
```php
wp_remote_get( string $url, array $args = array() );
```

# mail 보내기 
https://wphowto.net/smtp-mailer-plugin-for-wordpress-1482  
SMTP 플러그인으로 메일 서버 셋업 후 아래 function 사용  
```php
wp_mail( $to, $subject, $message, $headers, $attachments );
```
