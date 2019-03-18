.. ventana documentation master file, created by
   sphinx-quickstart on Tue Feb 26 12:30:48 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Ventana
===================================

.. toctree::
   :maxdepth: 1

   METs
   cutpoints
   sojourn

Examples
===================================

    .. code-block:: python

        import pandas as pd
        from ventana.sojourn import sojourn_1x

        df = pd.read_df("path")
        df["sojourn_est"] = sojourn_1x(df["y_counts"])



Indices and tables
===================================

* :ref:`modindex`
