This repository holds my attempts to allow interaction with [Spark](https://spark.apache.org/) on a local machine as well as on a remote cluster using Python from within [Jupyter](http://jupyter.org/).

Main steps:

  * Setup Spark on a local machine (DONE)
  * Execute simple Spark job(s) on a local machine from Jupyter (DONE)
  * Load CSV files into spark, using `spark_csv`
  * Link *local* notebook to a cluster instance of Spark and run jobs remotely. Here, it is important to understand how to setup the notebook where to execute Spark. Should be simple to toggle between the local and remote instances.
