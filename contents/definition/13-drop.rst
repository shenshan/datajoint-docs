Drop
====

The ``drop`` method completely removes the table from the database, including its definition.  It also removes all dependent tables, recursively.  DataJoint will first display the tables being dropped and the number of tuples in each before prompting the user to proceed.

The ``drop`` method is often used during the initial design to allow altered table definitions to take effect.

|matlab| Matlab
---------------

.. code-block:: matlab 

    % drop the Person table from the lab schema
    drop(lab.Person)  

|python| Python
---------------

.. code-block:: python

    # drop the Person table from its schema 
    Person().drop()

.. |python| image:: ../_static/img/python-tiny.png
.. |matlab| image:: ../_static/img/matlab-tiny.png
