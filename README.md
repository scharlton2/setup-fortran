# Setup Fortran

Changes from fortran-lang/setup-fortran@v1.6.1

  if: runner.os == 'Windows' && contains(inputs.compiler, 'intel')
   * Increased the time that the cache is valid by removing the date from the cache key
   * Only installs ifort (ie intel.oneapi.win.ifort-compiler is the only component installed)

