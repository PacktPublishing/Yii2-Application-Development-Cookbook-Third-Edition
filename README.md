# Yii2 Application Development Cookbook Third Edition
This is the code repository for [Yii2 Application Develoment Cookbook Third Edition](https://github.com/PacktPublishing/Yii2-Application-Development-Cookbook-Third-Edition?utm_source=github&utm_medium=repository&utm_campaign=9781785281761), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
##Instructions and Navigation




All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.
You will see something similar to the following:
```
 public function __construct($id, $module, ShoppingCart $cart, $config = [])
    {
        $this->cart = $cart;
        parent::__construct($id, $module, $config);
    }

    public function behaviors()
    {
        return [
            'verbs' => [
                'class' => VerbFilter::className(),
                'actions' => [
                    'delete' => ['post'],
                ],
            ],
        ];
    }

```
####Author Instructions


 HHVM is installed.

 Running PHP web scripts with HHVM is done by having your webserver talk to HHVM over FastCGI. Install nginx or Apache, and then:
* $ sudo /usr/share/hhvm/install_fastcgi.sh
* $ sudo /etc/init.d/hhvm restart
* (if using nginx)  $ sudo /etc/init.d/nginx restart
* (if using apache) $ sudo /etc/init.d/apache restart

Detailed FastCGI directions are online at:
* https://github.com/facebook/hhvm/wiki/FastCGI

If you're using HHVM to run web scripts, you probably want it to start at boot:
* $ sudo update-rc.d hhvm defaults

Running command-line scripts with HHVM requires no special setup:
* $ hhvm whatever.php

You can use HHVM for /usr/bin/php even if you have php-cli installed:
* $ sudo /usr/bin/update-alternatives --install /usr/bin/php php /usr/bin/hhvm 60

####Software and Hardware list
| Chapter  | Software required | OS required            |
| -------- | ------------------| ------------           |
| 1 to 12 |  Web Server, Database Server, PHP, Yii2          | Windows/Mac/Ubuntu     |



##Related Products
* [Yii 1.1 Application Development Cookbook](https://www.packtpub.com/web-development/yii-11-application-development-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781849515481)

* [Yii Application Development Cookbook - Second Edition](https://www.packtpub.com/web-development/yii-application-development-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781782163107)

* [Web Application Development with Yii 2 and PHP](https://www.packtpub.com/web-development/web-application-development-yii-2-and-php?utm_source=github&utm_medium=repository&utm_campaign=9781783981885)

### Suggestions and Feedback 
 [Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform)  if you have any feedback or suggestions.
