Draft

This is a proposal for the fundamental/core mathematics as well as for the theoretical/experimental mathematics

### 1) Axiom: Sum of all numbers = G

### 2) Each number(pr) is represented as t(pa, pr, fu), where t = time, pa = pr-pa, and fu = rand([pa-pr, pr, pa+pr])

NOTES: 
a) fu representation can be improved or extended (probably to infinity).

b) pa representation can also be improved (also probably to infinity).

c) Best way to improve fu and pa is through recursion but other methods can be used at a precision cost. So a balance is the key here.

### 3) Full proposed equation is therefore sum(G) = t(pa, pr, fu)

Python code is elementary so I will add it later

PRO TIP for simulation/implementation:

1) Either limit G to get ad infinitum resolution on 1 specific number
2) Limit everything to a specific value to get a specific resolution on a specific number
3) Most likely it is best to start with primes only as they would allow a good resolution at a sane compute cost

I.e. G[pr] = t[:60](pa, pr, fu) would produce ONE unified number at an hourly resolution and complete representation.

OR 

G[:360] = t[:360](pa[:360], pr, fu[:360]) would produce a year worth of unified numbers at a daily resolution and complete representation.
