# StudentDetails-PerformanceTest-JMeter
# Change branch main to master to see the project files.
Dear, I have completed Performance test on frequently used API for test Application.
Test executed for the below mentioned scenario in server.
50 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 15.0 And Total concurrent API requested:600. 
100 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 15.0 And Total concurrent API requested:600. 
200 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 17.6 And Total concurrent API requested:900. 
300 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 30.0 And Total concurrent API requested:1200. 
400 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 34.0 And Total concurrent API requested:1800. 
500 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 37.0 And Total concurrent API requested:2400. 
550 concurrent request with 1 loop count; Avg TPS for total Samples is ~ 31.0 And Total concurrent API requested:3000. 
While executed 550 concurrent request, found 916 request got connection timeout and error rate is 30.53%. 
Summary: Server can handle almost concurrent 2400 API, call with almost zero (0) error rate.
# Open Jmx file with JMeter and open HTML file with any browser.
