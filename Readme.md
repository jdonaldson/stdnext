# StdNext

StdNext is an alternative implementation of the [Haxe](http://www.haxe.org) std
library. It uses compiler techniques like type constraints in order to make 
certain functions more flexible.

Normally, these changes could be added directly to the standard library itself.
However, std lib api changes require an extra level of scrutiny and evaluation,
especially given the wide surface area of the haxe target implementations.
