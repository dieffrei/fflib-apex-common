# 1.0.0 (2019-12-06)


### Bug Fixes

* Bug where merge was not applied to registered record, and registered record was overwritten by new registration ([fea8037](https://github.com/dieffrei/fflib-apex-common/commit/fea8037c57f9908eb5c4d12b7226767457107c46))
* Fix refactor fails: UnitOfWork (Traction internal) instead of fflib_SObjectUnitOfWork ([bd5bffa](https://github.com/dieffrei/fflib-apex-common/commit/bd5bffa2aaf75d17342a686eaf3722c9d17ce6f9))
* Remove breaking change where exception would be thrown if subsequent register dirty called without dirty fields specified ([2d7ad73](https://github.com/dieffrei/fflib-apex-common/commit/2d7ad73158432c4178e2304df2014a4b28eb13db))
* When no dirty fields provided, overwrite the registered record ([7db6291](https://github.com/dieffrei/fflib-apex-common/commit/7db6291513a1805aa625ea785e4affc5f782c7ce))
* **ci:** add java support ([b629aac](https://github.com/dieffrei/fflib-apex-common/commit/b629aac9c858d80ef35b6ecebff324493ad7cb2b))
* **ci:** add node support ([76882c2](https://github.com/dieffrei/fflib-apex-common/commit/76882c2ca0654408cf9bf3afe962569015201b1b))
* **ci:** change node js support version to 10 ([3ef6055](https://github.com/dieffrei/fflib-apex-common/commit/3ef60556c0ac401056d12de02f1db405c790076d))
* **release:** change package definition to the right repository url ([39ac58c](https://github.com/dieffrei/fflib-apex-common/commit/39ac58c081f24672e6b20a14d9b7bc927e4d3f19))


### Features

* Add optional parameter for registerDirty to specify exactly what fields need to be updated ([08a5984](https://github.com/dieffrei/fflib-apex-common/commit/08a5984a29a365eb56390ebc7154ca74065b2bcf))
* Add test to ensure non breaking behaviour when overwriting existing registeredRecord ([dfce16d](https://github.com/dieffrei/fflib-apex-common/commit/dfce16d968b7b4a2a1700e085054db12c1372e18))
* **release:** add support release management ([0c00780](https://github.com/dieffrei/fflib-apex-common/commit/0c00780d9c98e536aedba14896da0d976f76712d))
