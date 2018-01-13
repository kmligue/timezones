# Timezones

This is a demo package to display time.

# Installation

    composer require kmligue/timezones:dev-master

add to your providers array **(config/app.php)**

    KMLigue\Timezones\TimezonesServiceProvider::class,

to publish the view file

    php artisan vendor:publish --tag=timezones