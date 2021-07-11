<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/batch.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

There are some supported batch commands:

    s3-secure batch encryption enable FILE.txt
    s3-secure batch encryption disable FILE.txt
    s3-secure batch policy enforce_ssl FILE.txt
    s3-secure batch policy unforce_ssl FILE.txt

The format of FILE.txt is a list of bucket names separated by newlines.  Example:

buckets.txt:

    my-bucket-1
    my-bucket-2

