# StudentDetails-PerformanceTest-JMeter
# Change branch main to master to see the project files.
Dear, I have completed Performance test on frequently used API for test Application.
Test executed for the below mentioned scenario in server.
50  concurrent request with 1 loop count; Avg TPS for total Samples is ~ 6.667 And Total concurrent API requested:400. 
100 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 13.33 And Total concurrent API requested:800. 
200 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 26.67 And Total concurrent API requested:1600. 
300 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 40.00 And Total concurrent API requested:2400. 
400 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 53.33 And Total concurrent API requested:3200. 
500 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 35.90 And Total concurrent API requested:4000. 
550 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 72.00 And Total concurrent API requested:4400. 
While executed 550 concurrent request, found 75 request got connection timeout and error rate is 1.7%. 
Summary: Server can handle almost concurrent 4000 API, call with almost zero (0) error rate.
# Open Jmx file with JMeter and open HTML file with any browser.
