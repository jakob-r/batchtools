# batchtools 0.9.1
* Deactivated swap for clusterFunctionsDocker.
* `findExperiments()` now has two additional arguments to match for regular expressions.
  The possibility to prefix a string with "~" to enable regular expression matching has been removed.
* Fixed listing of jobs for `ClusterFunctionsLSF` and `ClusterFunctionsOpenLava` (thanks to @phaverty).
* Fixed broken key lookup in some join functions.
* Fixed a bug where `getJobTable()` returned `difftimes` with the wrong unit (e.g., in minutes instead of seconds).
* Timestamps are now stored with sub-second accuracy.
* Job hashes are now prefixed with literal string 'job' to ensure they start with a letter as required by some SGE systems.

# batchtools 0.9.0

Initial CRAN release.
