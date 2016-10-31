##########
money-decimal2text
##########
    
Convert money decimal to text

.. image:: https://badge.fury.io/py/money-decimal2text.svg
    :target: https://pypi.python.org/pypi/money-decimal2text

=======
Install
=======

.. code-block:: bash

    pip install money-decimal2text

=======
Example
=======

.. code-block:: python

    from money_decimal2text.script import decimal_to_text
    import decimal

    int_units = ((u'рубль', u'рубля', u'рублей'), 'm')
    exp_units = ((u'копейка', u'копейки', u'копеек'), 'f')

    print decimal_to_text(decimal.Decimal('302.19'), int_units=int_units, exp_units=exp_units)
    # триста два рубля девятнадцать копеек


=======
License
=======

MIT
