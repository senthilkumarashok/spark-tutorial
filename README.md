# spark-cassandra-tutorial

## Cassandra

  * Distributed transactional database
  * Extremely high availability and partition tolerance
  * seamless multi data center support
## Spark

  * Distributed computing engine for big data and in memory processing
  * Fault tolerance
  
## Key Points - Spark

 * Spark Client - contains the driver & Spark Context .
 * Driver - entry point that contains the spark-context instance .
 * Spark Context - interface used to import , export and computing data  .
 * Master - scheduling and resource orchestration .
 * Worker - Maintain node state and running executors .
 * Executor - allocated per job and in charge of executing the tasks from the job .

# spark computation

 * Spark computes the network of operations in a graph which is DAG
 * Each DAG is converted to jobs
 * Each jobs composed of one or more stages
 * Each stages composed of one or more tasks

## MapReduce Vs Spark

  * Map Reduce is a two stage process whereas Spark form a DAG (Directed acyclic graph) for computation
  
## RDD - Resilent Distributed Datasets

  * can be cached in memory
  * For fault tolerance , each RDD stores its lineage graph of transformation that needs to be partially or fully executed to generate its RDD
  
## Main Components

  * spark-sql (shark its predecessor) - enables sql queries to be executed attop of spark
      => coupled with DataFrame abstraction makes powerful in doing data analysis.
  * MLLib - 
  * GraphX -
  * spark-streaming - 
  

  
  
  
