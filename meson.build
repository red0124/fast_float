project(
  'fast_float', 
  ['cpp'], 
  version: '0.7.0', 
  meson_version:'>=0.54.0')

fast_float_dep = declare_dependency(
  include_directories: include_directories('include'))

meson.override_dependency('fast_float', fast_float_dep)
