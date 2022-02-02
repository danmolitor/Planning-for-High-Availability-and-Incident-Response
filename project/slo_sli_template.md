# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability | Total 200 responses over total responses in the last minute | 99%                                                                                                         |
| Latency      | Histogram bucket showing 90th percentile request latencies for last 30 seconds | 90% of requests below 100ms                                                                                 |
| Error Budget | 1 - Number of successful requests over total number of requests, over the error budget | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   | Total number of successful requests over the last five minutes | 5 RPS indicates the application is functioning                                                              |
