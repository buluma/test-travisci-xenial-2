# Test Travis CI with Xenial VM

[![Build Status](https://travis-ci.com/buluma/test-travisci-xenial-2.svg?branch=main)](https://travis-ci.com/buluma/test-travisci-xenial-2) [![HitCount](http://hits.dwyl.com/buluma/docker-ubuntu1404-ansible.svg)](http://hits.dwyl.com/buluma/docker-ubuntu1404-ansible)

In general

 - Official Travis CI document: [Setting up Databases and Services](https://docs.travis-ci.com/user/database-setup/)


Postgres

 - **NEW!** Port number = 5432 (default).

 - Official tip: [Using a different PostgreSQL Version](https://docs.travis-ci.com/user/database-setup/#using-a-different-postgresql-version)

 - Authentication tip: https://github.com/travis-ci/travis-ci/issues/9624

Cassandra

 - **NEW!** Example: https://github.com/aio-libs/aiocassandra/blob/master/.travis.yml

RabbitMQ 

 - **NEW!** Install RabbitMQ: https://travis-ci.community/t/rabbitmq-on-xenial/1827

 - **NEW!** Install RabbitMQ management plugin: https://www.rabbitmq.com/management.html

 - Tip on Stack Overflow: [Declaring rabbitmq exchanges in travis build setup](https://stackoverflow.com/q/52107517/714426)
