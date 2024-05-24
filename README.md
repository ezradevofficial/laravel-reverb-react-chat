## Installations steps

Clone the project

run cp .env.example .env

run composer install

run php artisan migrate

run php artisan key:generate

run npm install

## Files Used in the project

app/Models/Message.php

database/migrations/2024_03_25_000831_create_messages_table.php

routes/web.php

app/Events/GotMessage.php

app/Jobs/SendMessage.php

app/Http/Controllers/HomeController.php

.env

config/reveb.php

config/broadcasting.php

routes/channels.php

resources/views/home.blade.php

resources/js/components/Main.jsx

resources/js/app.jsx

resources/js/components/Message.jsx

resources/js/components/MessageInput.jsx

resources/js/components/ChatBox.jsx

## Commands used

php artisan make:model -m Message

php artisan migrate:fresh

composer require laravel/ui

php artisan ui react --auth

php artisan make:event GotMessage

php artisan make:job SendMessage

php artisan install:broadcasting

### Running the application

npm run build

php artisan queue:listen

php artisan reverb:start

php artisan serve
