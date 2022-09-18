# Performance-Testing
Performance Testing performed in non - gui mode

Summary report of Performance Testing --- 

I've completed performance test on frequently used API for test Website.
Test executed for the below mentioned scenario in server https://www.banglapuzzle.com/ and the server ip is 198.54.126.144 


12 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 15 and Total Concurrent API requested:2172 
13 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 11 and Total Concurrent API requested:2353
14 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 13 and Total Concurrent API requested:2531 
15 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 15 and Total Concurrent API requested:2662 

while executing 15 concurrent requests, found 38 requests got connection timeout and error rate is 1.43%.

Summary: Server can handle almost concurrent 2550 API calls with less than (1.00) error rate.
