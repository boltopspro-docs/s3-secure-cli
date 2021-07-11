<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/lifecycle/add.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Example

    $ s3-secure lifecycle add a-test-bucket-in-us-east-1
    Added lifecycle policy to bucket a-test-bucket-in-us-east-1
    $

By default, the add command will only add a lifecycle policy if you none exists.

It may be useful to test adding an additional lifecycle policy, for this you can use both the `--additive` and `--prefix` options. Note, you must make sure that the lifecycle policies can work together. For example, they must have different prefixes.

    $ s3-secure lifecycle add a-test-bucket-in-us-east-1 --additive --prefix /foo
    Added lifecycle policy to bucket a-test-bucket-in-us-east-1
    $