Scala Environment
=================

This docker build creates a base image for running scala/sbt tasks
in conjunction with a continuous integration tool, such as [jenkins].


Loaded
------

The image is loaded with [sbt-extras] for support of any scala version. It comes
pre-seeded with the latest scala version (2.11.7) as well as node.js.


[sbt-extras]: https://github.com/paulp/sbt-extras
[jenkins]: https://jenkins-ci.org/

License
-------

[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0)
