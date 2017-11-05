# Implementation of CARED algorithm in ns-3

## Course Code: CS822

## Assignment: #GP1

### Overview
Cautious Adaptive RED (CARED) [1] is a two-in-one AQM algorithm that provides advantages of Adaptive RED (ARED) [2] and Refined Adaptive RED (RARED) [3]. The original paper of CARED used ns-2 [4] for comparing its performance against ARED and RARED. However, till date the implementation of CARED is not publicly available in any network simulator. This repository provides an implementation of CARED algorithm in ns-3 [5].

### CARED example	<br/>

An example program for CARED has been provided in

`examples/traffic-control/adaptive-red-variants.cc`

and should be executed as

`./waf --run "adaptive-red-variants --queueDiscType=CARED"`

### References

[1] Tahiliani, M. P., Shet, K. C., & Basavaraju, T. G. (2012). CARED: cautious adaptive RED gateways for TCP/IP networks. Journal of Network and Computer Applications, 35(2), 857-864.

[2] Floyd, S., Gummadi, R., & Shenker, S. (2001). Adaptive RED: An algorithm for increasing the robustness of RED’s active queue management.

[3] Kim, T. H., & Lee, K. H. (2006, October). Refined adaptive RED in TCP/IP networks. In SICE-ICASE, 2006. International Joint Conference (pp. 3722-3725). IEEE.

[4] http://www.isi.edu/nsnam/ns/

[5] http://www.nsnam.org/
