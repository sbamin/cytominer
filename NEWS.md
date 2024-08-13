# cytominer 0.2.2.9001

* Forked repo upto commit: c3c2efc750cf8dea5f85f389eab515d92fa47cd9
* Replaced default Map function with furrr: future_map to enable parallelization during normalization step.

# cytominer 0.2.2.9000

# cytominer 0.2.2

- Maintenance release in preparation for `dplyr 1.0.0` (#146)
- Improve tests and change robustize behavior (#141)

# cytominer 0.2.1

This is a minor release but contains several new functions as well as a long-pending fix for incompatibility with the new (2018) tidyeval API.

## New functions
- `whiten()` (#103)
- `extract_subpopulations()` (#107)
- `sparse_random_projection()` (#117)
- `svd_entropy()` (#123)
- `covariance()` (#114)

## Bug fixes
- Fixed tidyeval incompatibilities reported in #131,#133,#134 (#135)

# cytominer 0.1.0

Hello world!

