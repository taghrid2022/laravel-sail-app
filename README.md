<p>This is a sample laravel project with basic authentication enabled.</p>

<p>
This project is created using laravel with sail. In order to create a new project you need to have  <a href="https://www.docker.com/">Docker</a> installed.
</p>


Install php 8
Install compoer 
`composer install`

Copy .env.example -> .env
Edit DB configs

## Create a new laravel project
<p>Create a laravel project<br>
    curl -s "https://laravel.build/[project name]" | bash
</p>


<p>Access the project directory<br>
    cd [project name]
</p>

<p>Run the project locally using sail<br>
./vendor/bin/sail up
</p>

## Do database migration using sail
<p>./vendor/bin/sail artisan migrate</p>
