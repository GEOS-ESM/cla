# Contributors to GEOS-ESM Projects

:heavy_check_mark: - CLA Signed

:x: - CLA not yet signed

## MAPL

- Raffaele Montuoro ([@rmontuoro](https://github.com/rmontuoro)) - :x:
  - Properly set external grid into root GridComp ([MAPL/#609](https://github.com/GEOS-ESM/MAPL/pull/609))
  - Set CapGridComp clock to external clock if provided ([MAPL/#610](https://github.com/GEOS-ESM/MAPL/pull/610))
  - Enable building and installing as standalone library ([MAPL/#611](https://github.com/GEOS-ESM/MAPL/pull/611))
  - Improving use of external clock ([MAPL/#615](https://github.com/GEOS-ESM/MAPL/pull/615))
  - Add missing declaration statement ([MAPL/#667](https://github.com/GEOS-ESM/MAPL/pull/667))
  - Set return code for MAPL Cap and CapGridComp methods ([MAPL/#721](https://github.com/GEOS-ESM/MAPL/pull/721))
  - Remove duplicate and unnecessary use statements ([MAPL/#722](https://github.com/GEOS-ESM/MAPL/pull/722))
  - Remove unguarded FLAP dependencies ([MAPL/#781](https://github.com/GEOS-ESM/MAPL/pull/781))
  - Enable nearest-neighbor interpolation for ExtData ([MAPL/#788](https://github.com/GEOS-ESM/MAPL/pull/788))
- Lizzie Lundgren ([@lizziel](https://github.com/lizziel)) - :x:
  - Add new restart attributes to MAPL: bootstrapped and skip initial restart ([MAPL/#39](https://github.com/GEOS-ESM/MAPL/pull/39))
  - ExtData debug printing
    ([MAPL/#172](https://github.com/GEOS-ESM/MAPL/pull/172),
    [MAPL/#203](https://github.com/GEOS-ESM/MAPL/pull/203))
  - Bypass the majority of MAPL_FlapCapOptions.F90 if not using FLAP ([MAPL/#452](https://github.com/GEOS-ESM/MAPL/pull/452))
- Liam Bindle ([@LiamBindle](https://github.com/LiamBindle)) - :x:
  - Changed how ESMF return codes are included in MAPL_Exceptions.h ([MAPL/#26](https://github.com/GEOS-ESM/MAPL/pull/26))
  - Added missing stretched-grid support to MAPL_ExtDataGridChangeLev ([MAPL/#223](https://github.com/GEOS-ESM/MAPL/pull/223))
  - Updated CMakeLists to work with GEOS-ESM/ESMA_cmake#57 ([MAPL/#226](https://github.com/GEOS-ESM/MAPL/pull/226))
  - Changed memtot (and associated variables) to 64-bit integers ([MAPL/#591](https://github.com/GEOS-ESM/MAPL/pull/591))
- Sebastian David Eastham ([@sdeastham](https://github.com/sdeastham)) - :x:
  - Fix vertical flipping for 0-indexed arrays ([MAPL/#302](https://github.com/GEOS-ESM/MAPL/pull/302))
  - Targeted fix for incorrectly specified latitudes in archived data ([MAPL/#337](https://github.com/GEOS-ESM/MAPL/pull/337))
  - Remove need for HDF5 Fortran bindings ([MAPL/#693](https://github.com/GEOS-ESM/MAPL/pull/693))

## GOCART

- Raffaele Montuoro ([@rmontuoro](https://github.com/rmontuoro)) - :x:
  - NOAA UFS integration ([GOCART/#24](https://github.com/GEOS-ESM/GOCART/pull/24))
  - Fix memory corruption in nitrate component ([GOCART/#27](https://github.com/GEOS-ESM/GOCART/pull/27))
  - Compute and export total PM2.5 and PM10 for UFS ([GOCART/#40](https://github.com/GEOS-ESM/GOCART/pull/40))
  - Implement NOAA/ARL FENGSHA dust scheme ([GOCART/#50](https://github.com/GEOS-ESM/GOCART/pull/50))

## ESMA_cmake

- Raffaele Montuoro ([@rmontuoro](https://github.com/rmontuoro)) - :x:
  - Enable independent use with external packages ([ESMA_cmake/#133](https://github.com/GEOS-ESM/ESMA_cmake/pull/133))


