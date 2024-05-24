:github_url: xxx

OpenGSL Documentation
===================================

**OpenFGL** is a benchmark for Federated Graph Learning.
It provides a fair and comprehensive platform to evaluate existing FGL works and facilitate future FGL researches.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Citation
--------
Please cite our paper (and the respective papers of the methods used) if
you use this code in your own work:

::

   @article{xkLi_FedGTA_VLDB_2024,
     author       = {Xunkai Li and
                     Zhengyu Wu and
                     Wentao Zhang and
                     Yinlin Zhu and
                     Ronghua Li and
                     Guoren Wang},
     title        = {FedGTA: Topology-aware Averaging for Federated Graph Learning},
     journal      = {Proc. {VLDB} Endow.},
     volume       = {17},
     number       = {1},
     pages        = {41--50},
     year         = {2023},
     url          = {https://www.vldb.org/pvldb/vol17/p41-li.pdf},
     timestamp    = {Mon, 27 Nov 2023 13:13:34 +0100},
     biburl       = {https://dblp.org/rec/journals/pvldb/LiWZZLW23.bib},
     bibsource    = {dblp computer science bibliography, https://dblp.org}
   }


If you use our benchmark in your works, we would appreciate citations to the paper:

.. toctree::
   :glob:
   :maxdepth: 3
   :caption: Getting Started

   installation
   example
   fgl_tutorial


.. toctree::
   :glob:
   :maxdepth: 3
   :caption: Modules

.. toctree::
   :glob:
   :maxdepth: 3
   :caption: Resources

   fgl_studies

.. toctree::
   :glob:
   :maxdepth: 3
   :caption: Content

   usage
   api
