The R-package metagen
=====================

Introduction
------------

This is an R-package for inference in the random effects meta regression
model.  The purpose of the package is two fold.  On the one hand, it
allows the user to run different inferential methods on any given data
that may (or may not) follow a meta regression model.  The output is a
neat summary of all kinds of different methods, many commonly used for
an analysis and some more uncommon ones. The big feature are two methods
based on generalised inference principles.

On the other hand, the package allows to run rather sophisticated large
scale computer experiments that evaluate the performance of all
implemented methods with respect to coverage probability (and, well,
average length).  The idea is to use the above procedure to trace out
the possible magnitude of all unknown parameters, and then use the
possibility of running a computer experiment in a possible space of
parameters to get an idea of which method is in fact trustworthy.

Installation
------------

You may use the following magic to build and install the package on your
system:

```
make package
make install
```

Then open up an R-session and type:

```
library(metagen)
```

And you are good to go.

Where to start
--------------

Start to get a feel for the functionality of the package by having a
look at the help files of the functions `metareg` and `metagen`.

```
?metareg
?metagen
```

This should get you started very quickly.
