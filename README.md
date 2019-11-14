# loggly-shipper-snap

This snap connects to journald and ships logs to loggly.

## Install & Setup
```
snap install loggly-shipper
snap connect logglg-shipper:log-observe
snap set loggly-shipper customer-token=<your-customer-token>
```
