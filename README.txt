This is a modified version of Hive 0.7.1 HBase Handler to enable JSON
encoding/decoding in column values. The column specification looks like

<columnFamily>:<columnQualifier>[<subQUalifier>]

e.g.

summary:details[name]
summary:details[age]
summary:details[gender]

where summary:details is a column containing JSON data.

License: Apache 2, same as Hive

See http://wiki.apache.org/hadoop/Hive/HBaseIntegration for
information about the HBase storage handler.
