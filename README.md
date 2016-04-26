# Experimental Platform: redis

Redis is an open-source, networked, in-memory, key-value data store with optional durability. It is written in ANSI C. The development of Redis has been sponsored by Pivotal since May 2013; before that, it was sponsored by VMware. According to the monthly ranking by DB-Engines.com, Redis is the most popular key-value store. The name Redis means REmote DIctionary Server.

This is a component of the experimental platform. To read more about it please go here:

[https://github.com/experimental-platform/experimental-platform](https://github.com/experimental-platform/experimental-platform)

## Usage

    # build
    docker build -t "platform-redis:development" .
    # run
    docker run "platform-redis:development"
    # test
    ./test-image "platform-redis:development"

## Branch: Development

[![Build Status](https://travis-ci.org/experimental-platform/platform-redis.svg?branch=development)](https://travis-ci.org/experimental-platform/platform-redis)

All development branches stem from and (re-)integrate here.

## Branch: Master

[![Build Status](https://travis-ci.org/experimental-platform/platform-redis.svg?branch=master)](https://travis-ci.org/experimental-platform/platform-redis)

This is the base for α-channel releases.
