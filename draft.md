A conditional transform algorithm for `C++`

ISO/IEC JTC1 SC22 WG21 Programming Language `C++`

D??????

Working Group: Library Evolution

Date: 2017-10-16

_Jonathan Coe \<jonathanbcoe@gmail.com\>_

_Charlie Beattie \<cbeattie@somewhere.com\>_



## Introduction

We propose the addition of a conditional transform algorithm, `std::transform_if` to the standard library.
Design of `std::transform_if` should follow that in the Boost library. The
current omission of `transform_if` from the `C++` standard library is a cause
of some surprise for experienced programmers.

## Impact on the standard
This proposal is a pure library extension. It requires additions to be made to
the standard library header `<algorithm>`. 


## Technical specifications

To be adopted from Boost.

## Acknowledgements
The authors would like to thank Denis Teplyashin for prompting the conversation that spawned this proposal.


## References

[boost::transform_if] "boost C++ libraries: Function template transform_if"  
```<http://www.boost.org/doc/libs/1_62_0/libs/compute/doc/html/boost/compute/transform_if.html>```


