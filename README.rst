cryptop
=======
cryptop is a lightweight command line based cryptocurrency portfolio. 
Built on python and ncurses with simplicity in mind, cryptop updates in realtime.

.. image:: img\cryptop.png

Installation
------------

The easiest way to install cryptop is through pip

.. code:: bash

    sudo pip install cryptop

cryptop can be installed manually, download the repo and run

.. code:: bash

    sudo python setup.py install

pip and setup.py can be run with a --user flag if you would prefer
not to sudo.

Usage
-----

Start from a terminal.

.. code:: bash

    cryptop
    
Follow the on screen instructions to add/remove cryptocurrencies from your portfolio.

Customisation
-------------

Cryptop creates two config dotfiles in your home directory. .cryptop contains 
the holdings data for the porftolio.

.cryptopc contains light configuration/ricing options for colors and backgrounds.

.. image:: img\fall.png

.. image:: img\aesth.png

Credits
-------

Uses the `cryptocompare.com API 
<http://www.cryptocompare.com/>`_.

Support
------

My aim is to become a blockchain developer but I have a long way to go, if you
would like to support me on my journey here is my address.

BTC: 15wNW29q7XAEbC8yus49CWvt91JkhcdkoW

Disclosure
----------

I am not liable for the accuracy of this program’s output nor actions
performed based upon it.
