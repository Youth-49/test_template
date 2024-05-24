Tutorial
========================

Get Started
-----------

You can modify the experimental settings in ``/config.py`` as needed,
and then run ``/main.py`` to start your work with OpenFGL. Moreover, we
provide various configured jupyter notebook examples, all of which can
be found in ``/examples``.

Scenario and Dataset Simulation Settings
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code:: python

   --scenario           # fgl scenario
   --root               # root directory for datasets
   --dataset            # list of used dataset(s)
   --simulation_mode    # strategy for extracting FGL dataset from global dataset

Communication Settings
~~~~~~~~~~~~~~~~~~~~~~

.. code:: python

   --num_clients        # number of clients
   --num_rounds         # number of communication rounds
   --client_frac        # client activation fraction

FL/FGL Algorithm Settings
~~~~~~~~~~~~~~~~~~~~~~~~~

.. code:: python

   --fl_algorithm       # used fl/fgl algorithm

Model and Task Settings
~~~~~~~~~~~~~~~~~~~~~~~

.. code:: python

   --task               # downstream task
   --train_val_test     # train/validatoin/test split proportion
   --num_epochs         # number of local epochs
   --dropout            # dropout
   --lr                 # learning rate
   --optim              # optimizer
   --weight_decay       # weight decay
   --model              # gnn backbone
   --hid_dim            # number of hidden layer units

Evaluation Settings
~~~~~~~~~~~~~~~~~~~

.. code:: python

   --metrics            # performance evaluation metric
   --evaluation_mode    # personalized evaluation / global evaluation
