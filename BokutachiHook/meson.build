curl_dep = dependency('libcurl')
nlohmann_json_dep = dependency('nlohmann_json', version: '>= 3.9.0')

hook_incdir = include_directories('include')
hook_exec = library(
  'BokutachiHook',
  'src/dllmain.cpp',
  'src/mem.cpp',
  dependencies: [
    curl_dep,
    nlohmann_json_dep,
  ],
  install: true,
  include_directories: hook_incdir,
)
