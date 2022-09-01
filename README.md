# Jmeter-taurus-yaml
Creating a JMeter Script Using YAML 
====================================
Taurus’ simple configuration syntax to create a test scenario as a YAML file, with passing test configurations such as test duration, rampup,rampdown,number of virtual users.

To run Jmeter test,run the below command:
bzt /c/Gatling/test-scenario.yaml 

Note: put jmeter script and scenario file(yaml) in same directory.

Using BlazeMeter’s Reports
===========================
Another great advantage of running a JMeter script with Taurus is that you get access to BlazeMeter’s reporting service. While many of the testing tools focus on execution and less on reporting, this allows you to access test results in a convenient and interactive way, compare different executions, monitor trends over time, and collaborate with your colleagues. Plus you can use BlazeMeter’s reporting service even if you’re just running the ‘light’ free of charge version.

The easiest way to do this is to simply use the -report command line switch. This will send your results to BlazeMeter’s reporting service - and you won’t need to set anything else up. You’ll receive the link for your report in the console text, and this will be automatically be opened in your default browser.

bzt /c/Gatling/test-scenario.yaml -report
