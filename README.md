Module-Build-Prereq
===================

Perl module to naïvely analyze your module dependencies and then make
sure they're properly listed in your Makefile.PL.

INSTALLATION

To install this module type the following:

    perl Makefile.PL
    make
    make test
    make install

USAGE

    assert_modules(\%prereq_pm);

COPYRIGHT AND LICENCE

Copyright (C) 2013 by Scott Wiersdorf

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself, either Perl version 5.16.3 or,
at your option, any later version of Perl 5 you may have available.


