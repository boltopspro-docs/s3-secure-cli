<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/CHANGELOG.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

# Change Log

All notable changes to this project will be documented in this file.
This project *tries* to adhere to [Semantic Versioning](http://semver.org/), even before v1.0.

## [0.1.0]
- add commands: access_logs, lifecycle, versioning, remediate_all
- community version only has: encryption and policy
- s3 client is smarter and switches regions on a per-bucket basis

# Original Community Version Changelog

## [0.4.2]
- improve error message for Aws::STS::Errors::RegionDisabledException error

## [0.4.1]
- improve cli help

## [0.4.0]
-  #1 summary command

## [0.3.0]
- clean up policy_document method interface

## [0.2.0]
- encryption enable: add kms-key option

## [0.1.0]
- Initial release.
