## phpsh 

Simple read-eval-print loop for PHP with a few extra conveniences including:

- saveable command history. Incrementally produce tests! 
- catches (and displays) most errors
- auto-save on fatal crash, easy replay up to just before fatal command
- convenient display representation of evaluated expressions (__toString whre available, var_export where not)

Works with PHP 7+ (would likely work back through 4.2, replacing \Throwable with Exception). 

Works best if you're using PHP cli executable built with the `--with-readline` or `--with-libedit` options.
