.. sphinx-yaml-test documentation master file, created by
   sphinx-quickstart on Fri Oct 24 17:55:12 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

sphinx-yaml-test documentation
==============================

YAML in ``index.rst``:

.. code-block:: yaml

    ape:
      bear:
        cat:
          - dog: Bingo
            elephant: Dumbo
        frog:
          giraffe:
            - hedgehog: Spike
              ibex: Ike
          jaguar:
            koala:
              - llama: Larry
                moose: Molly

YAML included from ``animals.yaml``:

.. literalinclude:: animals.yaml
    :language: yaml
