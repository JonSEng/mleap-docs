# Core Concepts

MLeap uses several core building blocks to deployo your pipelines in an
easy-to-use manner.

| Concept | Description |
|---|---|
| Data Frames | Used to store data that is to be transformed, similar to a SQL table |
| Transformers | Take data from a data frame, apply some operation to it, and output new fields into the data frame |
| Pipelines | Use pipelines to execute a series of transformers against a data frame |
| MLeap Bundles | Used to store ML pipelines in a common JSON/Protobuf serialization format |
| MLeap Runtime | Used to execute an ML pipeline in the JVM using lightweight data structures |

