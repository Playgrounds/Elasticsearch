# Elasticsearch Playground

This is a simple Playground to containing a [Elasticsearch](http://elasticsearch.org) Daemon. Mainly
created for playing around with the search index for demoing or testing
purposes.


## Details

The VM is based on Ubuntu 14.04 including the following services and packages
installed:

- Oracle Java 7
- Elasticsearch 1.2.x

The IP address of the VM is `10.152.149.101`.

After the VM is booted the **Elasticsearch** service can be reached at port
`9200`.

## Installation

The following steps are needed in order to utilize this Playground:

1. Checkout the git repository
```
$ git clone git@github.com:Playgrounds/Elasticsearch.git
```

2. Initialize all needed ansible roles using [Composer](http://getcomposer.org)
```
$ cd Automation && composer install
```

3. Make vagrant build the VM for you
```
$ vagrant up
```
