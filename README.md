# ghhdb-Github-Hacking-Database
Github Hacking Database - A collection of Github's Dorks to search for Confidential Information (Yes, it's a Github version of Google Dorks)

### API Keys

Search | Description
--------- | ------
"api_hash" "api_id" "user_phone"|Telegram APP Configuration Keys (https://my.telegram.org/apps)
"aws_access_key_id" "aws_secret_access_key"|AWS API Keys
"cloudflare_api_key" "cloudflare_email"|Cloudflare API Key and Email
"Client ID" "client secret" "verification token"|Slack bot API Key
"xoxp-"|Slack API Key
"https://hooks.slack.com/"|Slack Incoming WebHook API Url
filename:passwords.txt|Passwords saved in text file
filename:passwords.doc|Passwords saved in doc file (See also .docx extesion)
"app.secret_key" extension=py|flask-login API Key
"app.config['SECRET_KEY']" extension:py|Flask Secret Key

### Certificates

Search | Description
--------- | ------
"-----BEGIN RSA PRIVATE KEY-----"|RSA Private Key 
"-----BEGIN PRIVATE KEY-----"|Unencrypted PKCS#8 and base64 encoded Private Key
"-----BEGIN ENCRYPTED PRIVATE KEY-----"|PEM file Private Key
"-----BEGIN CERTIFICATE-----" extension:pem| PEM encoded SSL certificate

### Source Code Leak/Reverse Engineering

Search | Description
--------- | ------
"package com.whatsapp" extension:java|Look for code leak or reverse engineer of an Android Application.
