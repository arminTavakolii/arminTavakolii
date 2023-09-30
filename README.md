```php
$personalInfo = [
    'name' => 'Armin',
    'birthday' => '4 jan 2003',
    'skills' => [
        'frontend' => ['html','css','javascript , ...'],
        'backend' => ['php','laravel','restful api , ...']
    ],
];
$json = json_encode($personalInfo, JSON_PRETTY_PRINT);
http_response_code(202);
echo $json;
```
