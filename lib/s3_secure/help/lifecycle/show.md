<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/lifecycle/show.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    $ s3-secure lifecycle show a-test-bucket-in-us-east-1
    This S3 bucket has lifecycle rules
    Bucket lifecycle details:
    {:rules=>
      [{:expiration=>{:expired_object_delete_marker=>true},
        :id=>"s3-secure-automated-cleanup",
        :prefix=>"/bar",
        :status=>"Enabled",
        :noncurrent_version_expiration=>{:noncurrent_days=>365},
        :abort_incomplete_multipart_upload=>{:days_after_initiation=>30}}]}
    $