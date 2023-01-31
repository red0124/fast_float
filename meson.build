project(
  'fast_float', 
  ['cpp'], 
  version: '0.7.0', 
  meson_version:'>=0.50')

fast_float_dep = declare_dependency(
  include_directories: include_directories('include'))

if meson.version().version_compare('>=0.54.0')
    meson.override_dependency('fast_float', fast_float_dep)
endif
