BitLuck
=======
A simple Bitcoin-based lottery script.

**WARNING**: This script comes with absolutely no warranty. This was an example showing how the Bitcion JSON-RPC works. **@PhilG has pointed out that [there is a bug in this script](https://github.com/JohnMaguire/BitLuck/issues/1) which would result in players being able to play for free after their first entry.**

Installation
------------
Set the configuration variables in `config.inc.php`.

Add a call in your crontab to run `give_prize.php` every day at the `$draw_time` time.

Create an address with the label "Lottery Pot" in the Bitcoin wallet you are using for BitLuck.

Make sure the wallet has enough funds to cover transaction fees.

License
-------
This code is licensed under the MIT license. More information can be found in the `LICENSE` file.
