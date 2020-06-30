# elk-shippers
Elastic shipper using Logstash or Beats

* Different way to ship your log files to ELK
  * Logstash with grok patter and exception stack trace handling
  * File Beat with Log message and multiline support for stack trace handling
* Heart Beat is also used to check status of health of applications
* File Beat can also be used to send JSON logs to ELK
* Metrics Beat should be used for Infra and system metrics

