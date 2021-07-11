<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/summary.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    $ s3-secure summary
    Determining bucket security-related settings...
    +----------------------------+------+------------+
    |           Bucket           | SSL? | Encrypted? |
    +----------------------------+------+------------+
    | a-test-bucket-in-us-east-1 | yes  | no         |
    | a-test-bucket-in-us-west-1 | no   | no         |
    +----------------------------+------+------------+
    $

There are `--ssl no` and `--encrypted no` filtering options:

    $ s3-secure summary --ssl no --encrypted no
    Determining bucket security-related settings...
    +----------------------------+------+------------+
    |           Bucket           | SSL? | Encrypted? |
    +----------------------------+------+------------+
    | a-test-bucket-in-us-west-1 | no   | no         |
    +----------------------------+------+------------+
    $