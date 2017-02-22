### Real-time stream processing 

* Database-like environment
 * **Stream** concept replaces **table** concept
* Stream processors access ingested events in real-time without intermediate disk operations
 * Performs much better than a database - database-reindex - query round-trip
 * Only current stream data is available to process 
 * *Windowed* operations: moving averages, counts, aggregates, thinning and filtering

