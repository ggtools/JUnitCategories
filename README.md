JUnit Categories
================

JUnit 4.9 introduced a nice [Category](http://junit.org/javadoc/4.10/org/junit/experimental/categories/Category.html)
annotation to classify you tests. While TestNG chose to use strings for the [test groups](http://testng.org/doc/documentation-main.html#test-groups)
JUnit categories use classes. This is way more flexible than strings this can be a pain when using multi-module maven
projects (see JUnit's [issue 400](https://github.com/junit-team/junit/issues/400)] for more details) especially
since JUnit does not ship with any categories.

This project tries to answer this issue by supplying a set of basic categories.

Licence
-------

This is public domain meaning you can do whatever you want with it.
