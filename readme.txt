=== Random Code Generator ===
Contributors: Joe Casabona
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6650099
Tags: random, code, generator, promotional, generate, store, verify
Requires at least: 2.7
Tested up to: 2.8.1
Stable tag: 1.0

 A simple plugin that genrates a random string of characters and stores it in a database. Good for generating promotional codes 

== Description ==

 A simple plugin that genrates a random string of characters and stores it in a database. By default the length is 10 characters (A-Z, a-z, 0-9, @!@#$%^&*()) and the strings are unique. 

== Installation ==

1. Upload random-code.php to the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place the `<?php rndcode_print_code(); ?>` template tag somewhere in your theme.

== Frequently Asked Questions ==
= How do I use this? =
Just follow the instructions! All generated codes will show up in the WordPress Admin Panel under Tools->Random Code Generator

= How can I style teh code? =
Just add a `.rndcode_code style` to your CSS. 


== Other Information ==

The template tags for this plugin are: 

1) `<?php rndcode_print_code(); ?>`: Will generate and print out a random 10 character string.

2) `<?php rndcode_generate_code([ $length); ?>`: Will generate a random string of `$length` charcters. `$length` is an optional argument. Default is 10. 

For more information, include release updates, bugs, and new features, you can go to [The Official Homepage](http://www.manifestdevelopment.com/wordpress-packages/code-generator/)