# SparkAndInMemoryCacheIntegration
In this repository we have an example for - How to read data from Source location (e.g. HDFS) and load that data in In Memory Cache (e.g. Gemfire). The main core of this example is - connecting In Memory Cache Server from Worker Nodes. So the data spark will read from source will not be collected on Driver node, it will directly get stored on Gemfire Server.
