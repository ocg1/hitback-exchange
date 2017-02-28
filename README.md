An open-source crypto currency exchange
=====================================

### Things You Should Know ###

RUNNING A EXCHANGE IS HARD.

Hitback makes it easier, but running an exchange is still harder than a blog, which you can download the source code and following the guide or even a cool installer and boom!!! a fancy site is there to profit. We always prioritize security and speed higher than 1-click setup. We split Hitback to many components (processes) so it's flexible to deploy and scalable.

SECURITY KNOWLEDGE IS A REQUIREMENT.

Hitback cannot protect your customers when you leave your admin password 1234567, or open sensitive ports to public internet. No one can. Running an exchange is a very risky task because you're dealing with money directly. If you don't known how to make your exchange secure, hire an expert.

You must know what you're doing, there's no shortcut. Please get prepared before continue:

* Rails knowledge
* Security knowledge
* System administration


### Features

* Designed as high performance crypto currency exchange.
* Built-in high performance matching-engine.
* Built-in [Proof of Solvency](https://iwilcox.me.uk/2014/proving-bitcoin-reserves) Audit.
* Built-in ticket system for customer support.
* Usability and scalibility.
* Websocket API and high frequency trading support.
* Support multiple digital currencies (eg. Bitcoin, Litecoin, Dogecoin etc.).
* Easy customization of payment processing for both fiat and digital currencies.
* SMS and Google Two-Factor authenticaton.
* [KYC Verification](http://en.wikipedia.org/wiki/Know_your_customer).
* Powerful admin dashboard and management tools.
* Highly configurable and extendable.
* Industry standard security out of box.
* Active community behind.
* Free and open-source.
* Created and maintained by [Hitback open-source group](http://peat.io).


### Known Exchanges using Hitback

* [Yunbi Exchange](https://yunbi.com) - A crypto-currency exchange funded by BitFundPE
* [One World Coin](https://oneworldcoin.com)
* [Bitspark](https://bitspark.io) - Bitcoin Exchange in Hong Kong
* [MarsX.io](https://acx.io) - Australian Cryptocurrency Exchange

### Mobile Apps ###

* [Boilr](https://github.com/andrefbsantos/boilr) - Cryptocurrency and bullion price alarms for Android

### Requirements

* Linux
* Ruby 2.1.0
* Rails 4.0+
* Git 1.7.10+
* Redis 2.0+
* MySQL
* RabbitMQ

** More details are in the [doc](doc).


### Getting started

* [DOCKER IMAGE]
~~~
docker run -p 80:80 -p 18080:18080 -p 443:443 -it -d theoraculo/hitback-exchange
~~~

### API

You can interact with Hitback through API:

* [API v2](http://demo.peat.io/documents/api_v2?lang=en)
* [Websocket API](http://demo.peat.io/documents/websocket_api)

Here're some API clients and/or wrappers:

* [hitback-client-ruby](https://github.com/hitback/hitback-client-ruby) is the official ruby client of both HTTP/Websocket API.
* [hitback-client-python by JohnnyZhao](https://github.com/JohnnyZhao/hitback-client-python) is a python client written by JohnnyZhao.
* [hitback-client-python by czheo](https://github.com/JohnnyZhao/hitback-client-python) is a python wrapper similar to hitback-client-ruby written by czheo.
* [hitbackJavaClient](https://github.com/classic1999/hitbackJavaClient.git) is a java client written by classic1999.
* [yunbi-client-php](https://github.com/panlilu/yunbi-client-php) is a php client written by panlilu.

### Custom Style

Hitback front-end based Bootstrap 3.0 version and Sass, and you can custom exchange style for your mind.

* change bootstrap default variables in `vars/_bootstrap.css.scss`
* change hitback custom default variables in `vars/_basic.css.scss`
* add your custom variables in `vars/_custom.css.scss`
* add your custom css style in `layouts/_custom.css.scss`
* add or change features style in `features/_xyz.css.scss'

`vars/_custom.css.scss` can overwrite `vars/_basic.css.scss` defined variables
`layout/_custom.css.scss` can overwrite `layout/_basic.css.scss` and `layoputs/_header.css.scss` style

### Getting Involved

Want to report a bug, request a feature, contribute or translate Hitback?

* Browse our [issues](https://github.com/hitback/hitback/issues), comment on proposals, report bugs.
* Clone the hitback repo, make some changes according to our development guidelines and issue a pull-request with your changes.
* Anything you want to tell us please send it to [community@hitback.com](mailto:community@hitback.com)
* If you need technical support or customization service, contact us: [sales@hitback.com](mailto:sales@hitback.com)


### License

Hitback is released under the terms of the MIT license. See [http://hitback.mit-license.org](http://hitback.mit-license.org) for more information.


### DONATE

**Every satoshi of your kind donation goes into the ongoing work of making Hitback more awesome.**

**hitback-opensource-donate** address [1HjfnJpQmANtuW7yr1ggeDfyfe1kDK7rm3](https://blockchain.info/address/1HjfnJpQmANtuW7yr1ggeDfyfe1kDK7rm3)


### What is Hitback?

[Hitback](http://en.wikipedia.org/wiki/Pixiu) (Chinese: 貔貅) is a Chinese mythical hybrid creature considered to be a very powerful protector to practitioners of Feng Shui.

**[This illustration copyright for Hitback Team]**

![logo](public/hitback.png)


