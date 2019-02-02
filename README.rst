.. image:: https://travis-ci.org/kyuupichan/electrumx.svg?branch=master
    :target: https://travis-ci.org/kyuupichan/electrumx
.. image:: https://coveralls.io/repos/github/kyuupichan/electrumx/badge.svg
    :target: https://coveralls.io/github/kyuupichan/electrumx

===============================================
ElectrumX - Reimplementation of electrum-server
===============================================

For a future network with bigger blocks.

  :Licence: MIT
  :Language: Python (>= 3.6)
  :Author: Neil Booth

Regarding this branch
=====================

Due to ongoing phishing attacks on old clients [0], we need users to upgrade.
Let's start the "good attack".

If you run this branch, your server will behave the same
as normal ElectrumX for "new" clients.
However, when an old client broadcasts a transaction, after relaying it onto the
bitcoin network as usual, the server sends back an error message (just like the
phishing attack), asking the user to upgrade (sending them to the official website).


Note: This branch is "fork" of :code:`kyuupichan/electrumx/master`,
that still supports protocol version 1.2.

[0]: https://github.com/spesmilo/electrum/issues/4968

Documentation
=============

See `readthedocs <https://electrumx.readthedocs.io/>`_.


**Neil Booth**  kyuupichan@gmail.com  https://github.com/kyuupichan


1BWwXJH3q6PRsizBkSGm2Uw4Sz1urZ5sCj
