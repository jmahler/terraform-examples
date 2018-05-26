
## NAME

aws_hello_world - server that returns hello world

## DESCRIPTION

This example will create an EC2 instance (terraform apply)
which starts a server on port 8080 that will return "Hello, World"

    $ curl ec2-54-149-202-206.us-west-2.compute.amazonaws.com:8080
    Hello, World

Note, if it doesn't work and you can't connect to the port make
sure you are using an ami with busybox installed.  An easy way
to check is to spin up an instance and check.  If it isn't installed,
install it, create a new ami, and then it should work.

This example was derived from the example in "Terraform: Up and Running"
by Yevgeniy Brikman [[1] Pg. 58].

[1]: https://www.oreilly.com/library/view/terraform-up-and/9781491977071/

## AUTHOR

Jeremiah Mahler <jmmahler@gmail.com>
