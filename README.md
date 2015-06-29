# heater
Tool to warm up AWS elastic load balancers

The general idea of this project is a load generation tool that can be used to hit a service and increase load over time.  I want to have both a feedback mechanism that can be used to decide how load increases as well as periodically re-scanning DNS to determine when the ELB service has scaled up.
