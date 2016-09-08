## Cron jobs on Aws ElasticBeanstalk Worker

[Worker Environment](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features-managing-env-tiers.html) documentation.

#### Usage:

- **/.ebextensions/01php.config** - PHP include_path can be set here ([documentation](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/ebextensions.html))
- **/cron.yaml** - cron jobs list ([documentation](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features-managing-env-tiers.html#worker-periodictasks))
- **/app** - set as HTTP path in the [Worker Configuration](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features-managing-env-tiers.html#using-features-managing-env-tiers-worker-settings)