# Install Command
#### 1 - php artisan make:command Repository
#### 2 - open app/Console/Kernel.php
#### 3 - Add new Command in protected $commands = [Repository::class]
#### 4 - Replace your File to our file 
#### 5 - php artisan config:cache
#### 6 - composer dump-autoload

# Using of Command
#### php artisan create:repo NameOfYourRepo

# if you want serivce for your repo
#### php artisan create:repo NameOfYOurRepo --service
