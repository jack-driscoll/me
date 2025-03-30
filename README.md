#!/bin/sh
# IN THE OLD COUNTRY YOU WOULD HAVE TO................................STOP HERE|
# hi, it's me, jack-driscoll and this is all about me
# of course, if you're reading this, it's about you, to
# FUCK CROSS COMPATIBILITY! Powershell be damned, POSIX 4 LYFE!
#-------------------------------------------------------------------------------
printf "What is your name?: " >&2
read -r option
echo "StackExchange users put a gun to my head and made me use printf,"
printf '%s\n' "$option"
echo ""
echo "Me, I would have just used echo"
