### Event sourcing for "fast data" and "slow data" 

* Data that is captured is represented as a log, not a relational model
 * No longer an intricately modelled "gold standard" reference of slowly changing corporate data
 * A time series of *immutable facts*, a replayable changelog
* We can rebuild: 
 * (system state at time t) = SUM (events logged up to time t)

* The idea behind event sourcing is an *old new thing*, it's already used in DBMS behind the scenes for indexing, journalling, incremental backup and other auxiliary functions 


