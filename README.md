Without `sphinx_toolbox` enabled:

![](without-toolbox.png)

With `sphinx_toolbox` enabled:

![](with-toolbox.png)

Notice that `elephant` has the wrong amount of indentation.

Source:

```rst
.. code-block:: yaml

   ape:
     bear:
       cat:
         - dog
           elephant

.. code-block:: yaml

   frog:
     goat:
       - hedgehog
         ibex
```
