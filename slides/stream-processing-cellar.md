### Real-time stream processing 

* Stream processors access ingested events in real-time without intermediate disk operations
 * Performs better than an update, reindex, query cycle on a database
 * **But** only current stream data is available to process 
 * *Windowed* operations: moving averages, counts, aggregates, thinning and filtering

