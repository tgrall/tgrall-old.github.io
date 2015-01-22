---
layout: post
title: "Screencast : Fun with Couchbase MapReduce and Twitter"
date: 2013-04-29 08:51:36 +0100
comments: true
categories: couchbase twitter nosql
---
I have created this simple screencast to show how you can, using Couchbase do some realtime analysis based on Twitter feed.

The key steps of this demonstration are

1.  Inject Tweets using a simple program available on my Github [Couchbase-Twitter-Injector](https://github.com/tgrall/couchbase-twitter-injector)
2.  Create views to index and query the Tweets by
    * User name
    * Tags
    * Date

The views that I used in this demonstration are available at the bottom of this post.

{% youtube X167R0TV5QE %}

Views:

{% gist 1df10b10c9dd387995cb %}
