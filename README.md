# laravel-package-demo2
test form laravel package

##install

composer update readytan/packagetest

##provider  app/config.php 

Readytan\Packagetest\PackagetestServiceProvider::class

##alias

'Packagetest' => Readytan\Packagetest\Facades\Packagetest::class 

##dump-autoload

composer dump-autoload
##publish

 php artisan vendor:publish –provider="Readytan\Packagetest\PackagetestServiceProvider" 
 