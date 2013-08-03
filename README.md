BitLuck
=======
A simple Bitcoin-based lottery script.

Installation
------------
Set the configuration variables in config.inc.php.

Add a call in your crontab to run give_prize.php every day at the `$draw_time` time.

Create an address with the label "Lottery Pot" in the Bitcoin wallet you are using for BitLuck.

Make sure the wallet has enough funds to cover transaction fees.

License
-------
This code is licensed under the ["Do I Look Like I Give A Shit" License](http://blog.samuellevy.com/post/46-do-i-look-like-i-give-a-shit-public-license.html).
