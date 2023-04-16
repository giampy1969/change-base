# change-base
Change number base (radix) - Feb 1994

B = chb(A,a,b) change numerical base:
a,b scalars from 2 to 64 , A,B strings.
Number A in base a , expressed in base b by B.
Symbols are 0 .. 9 A .. Z a .. z @ &.

Example:
'-54.13'-chb(chb('-54.13',6,27),27,6)

Note: since it operates by converting to 
and from doubles, it is not perfectly reliable 
for very long numbers in high bases.

Giampiero Campa 21-2-94
