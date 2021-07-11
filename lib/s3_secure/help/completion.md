<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/s3-secure-cli/blob/master/lib/s3_secure/help/completion.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    s3-secure completion

Prints words for TAB auto-completion.

    s3-secure completion
    s3-secure completion hello
    s3-secure completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(s3-secure completion_script)

Auto-completion example usage:

    s3-secure [TAB]
    s3-secure hello [TAB]
    s3-secure hello name [TAB]
    s3-secure hello name --[TAB]
