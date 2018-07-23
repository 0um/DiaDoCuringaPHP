# DiaDoCuringaPHP
[![Build Status](https://travis-ci.org/0um/DiaDoCuringaPHP.svg?branch=master)](https://travis-ci.org/0um/DiaDoCuringaPHP) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/989552569e374f8f94d1581b3734d1ba)](https://www.codacy.com/app/0um/DiaDoCuringaPHP?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=0unit/DiaDoCuringaPHP&amp;utm_campaign=Badge_Grade)

A Gregorian calendar converter to an annual calendar with 364 days, each representing a playing card. Divided into 52 weeks and 13 months, all with 28 days. Day 365 is an extra day, the day of the wildcard. Every four years to two extra days the double day of the wildcard.

The count of years begins in 1790

Taking into account the southern hemisphere! The seasons of the year are marked by different suits thus providing the suits of the months.

* Autumn is club
* Summer and is golds
* Spring is cup
* Winter is swords

## Required
```
> php composer.phar install
```

### For Debug
Install dom and xdebug
```
sudo apt-get install php-xml php-xdebug
```

## Run tests
```
> ./vendor/bin/phpunit tests
```

## Run test coverage
```
> ./vendor/bin/phpunit tests --coverage-html coverage
```

## Use
Copy the **src** to the PHP server, or initialize in this path

## My use ;)
I utilize this version to populate a twitter account <https://twitter.com/calencur>
