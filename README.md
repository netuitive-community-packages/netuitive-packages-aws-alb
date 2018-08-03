# netuitive.packages.aws.alb

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/aws.htm).

## Release History

### Version next

* Correct ACE configuration scope entry
* Updated policies for sudden change of load balancer errors, target response time, and request counts
* Add an element detail dashboard for Target Groups

### Version 1.3.0

* Add a Target Group Service Reliability Index computed metric

### Version 1.2.0

* Add 4xx error percent, 5xx error percent, total errors, and error percentage as computed metrics for Target Groups

### Version 1.1.0

* Add Target Group compatibility and ACS configs
* Updating validation to use metricly-cli
* Adding build notifications

### Version 1.0.0

* Initial production release of the package for monitoring AWS Application Load Balancer (ALB) resources.
