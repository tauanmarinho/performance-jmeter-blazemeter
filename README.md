# performance-jmeter-blazemeter
Performance tests with J-Meter and Blazemeter

Target: https://blazedemo.com/

Test case: Home > Reserve > Purchase > Confirm

Command line execution locally:
```
jmeter -n -t path/PERFORMANCE-JMETER-BLAZEMETER.jmx -l path/result.jtl -e -o path/report
```