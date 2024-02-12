I would be very grateful if you like PHFlow repository :)
```php
$personalInfo = [
    'name' => 'Armin Tavakoli',
    'birthday' => '4 jan',
    'skills' => [
        'frontend' => ['html','css','javascript , vue js , ...'],
        'backend' => ['php','laravel','restful api , ...']
    ],
];
$json = json_encode($personalInfo, JSON_PRETTY_PRINT);
http_response_code(202);
echo $json; 
```
