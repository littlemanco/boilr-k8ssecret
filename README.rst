====================
k8ssecret
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it easy to create Kubernetes secrets, in a format that I like

Similar Work
''''''''''''

None


Justification
'''''''''''''

Saves me time, and makes the files more consistent


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download littlemanco/boilr-k8ssecret k8ssecret
  
Updates
-------

I update these templates regularly. If you need to fetch the newer version, try this:

.. Code:: bash

  $ boilr template download littlemanco/boilr-k8ssecret k8ssecret -f 

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use k8ssecret .
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
