# msegat-API
msegat api php class

this is just a simple api for msegat website with two functions 

the first one to send sms

example 
```
$sms = new Sms(username, password, sender);

$teles = array("955xxxxxxx", "955xxxxxxxx");

$message = "this is test message";

$timeToSend = "2022-01-18 15:07:27";

$sms->send($teles, $message, $timeToSend);


```

the second is to get your credit 
example

```
$credit = $sms->getCredet();

```

if you want more functions or apis just contact me

http://hobrt.me
