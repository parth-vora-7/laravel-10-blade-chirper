## Set below in .env file

- QUEUE_CONNECTION=database
- MAIL_MAILER=smtp
- MAIL_HOST=sandbox.smtp.mailtrap.io
- MAIL_PORT=2525
- MAIL_USERNAME=USERNAME_FROM_MAILTRAP
- MAIL_PASSWORD=PASSWORD_FROM_MAILTRAP
- MAIL_ENCRYPTION=tls
- MAIL_FROM_ADDRESS="hello@example.com"
- MAIL_FROM_NAME="${APP_NAME}"

## Run below commands

- php artisan migrate
- npm run dev (keep running)
- php artisan queue:work (keep running)
- php artisan server (keep running)