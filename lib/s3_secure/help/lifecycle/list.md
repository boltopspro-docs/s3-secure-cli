<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/lifecycle/list.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    $ s3-secure lifecycle list
    +----------------------------+----------------------+
    |           Bucket           | Has Lifecycle Rules? |
    +----------------------------+----------------------+
    | a-test-bucket-in-us-east-1 | false                |
    | a-test-bucket-in-us-west-1 | true                 |
    +----------------------------+----------------------+
    $ s3-secure lifecycle list --lifecycle true
    +----------------------------+----------------------+
    |           Bucket           | Has Lifecycle Rules? |
    +----------------------------+----------------------+
    | a-test-bucket-in-us-west-1 | true                 |
    +----------------------------+----------------------+
    $ s3-secure lifecycle list --lifecycle false
    +----------------------------+----------------------+
    |           Bucket           | Has Lifecycle Rules? |
    +----------------------------+----------------------+
    | a-test-bucket-in-us-east-1 | false                |
    +----------------------------+----------------------+
    $