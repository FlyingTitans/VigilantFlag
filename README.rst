************
VigilantFlag
************

VigilantFlag is a distributed NIMS ICS management and training system.



Contribution
============




Repository Process
==================

1. The ``deployed`` branch contains the current released version.

2. The ``master`` branch contains code approved for the next release.

   a. Change version IAW `PEP440 <https://www.python.org/dev/peps/pep-0440/>`_.
      
   b. Merge ``master`` into ``deployed``.
   
   c. Create annotated tag marking the new version.

   d. Publish the new version.

3. New development shall occur on a branch with name ``dev/<number>_<desc>``
   or ``dev/<number>``.

   a. When completed a pull request into ``master`` shall be created; a PR
      into ``deployed`` may occur for a critical bug fix which will require
      ``deployed`` to be marked with a micro version tag and published.
   
   b. The pull request shall be squashed.



Legal
=====

- `Copyright <https://github.com/FlyingTitans/VigilantFlag/blob/master/COPYRIGHT>`_

- `License <https://github.com/FlyingTitans/VigilantFlag/blob/master/LICENSE>`_

