# 1.0.1 2014-10-26

* Uncommited transaction now generate automatic rollback
* Add tests about transactions

# 1.0.0 2014-10-24

* Now ``Promise.using`` of ``bluebird`` npm module is used to release the connection to the pool.
* Update the ``bluebird`` npm module.
* DBH: Adding ``bool verbose`` option in the constructor to debug the generated SQL to the console.
* DBH: ``DBH.escape`` now returns unquoted string.
* Update README.md

# 0.1.0

* Connection: Adding ``fetchOne``, ``fetchAll`` and ``fetcColumn`` methods.
* DBH: Adding ``escape``, ``sqlOrderBy`` and ``limit`` static methods.

# 0.0.1 2014-05-04

First version
