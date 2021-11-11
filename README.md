<p>This is a sample laravel project with basic authentication enabled.</p>

<p>
This project is created using laravel with sale. In order to create a new project you need to  <a href="https://www.docker.com/">Docker</a> installed.
</p>


## Create a new laravel project
-- Create a laravel project 
curl -s "https://laravel.build/[project name]" | bash

-- Access the project directory
cd [project name]

-- Run the project locally using sail
./vendor/bin/sail up


## Do database migration using sail
./vendor/bin/sail artisan migrate
