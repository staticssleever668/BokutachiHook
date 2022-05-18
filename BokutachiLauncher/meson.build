nlohmann_json_dep = dependency('nlohmann_json', version: '>= 3.9.0')

launcher_incdir = include_directories('include')
launcher_exec = executable(
  'BokutachiLauncher',
  'src/GetAuth.cpp',
  'src/Injector.cpp',
  'src/LaunchGame.cpp',
  'src/Main.cpp',
  dependencies: [
    nlohmann_json_dep,
  ],
  install: true,
  include_directories: launcher_incdir,
)
