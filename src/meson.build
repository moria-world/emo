cli_sources = [
    'cli/args.c',
    'cli/main.c',
    'cli/messages.c',
]

core_sources = [
    'core/chunk.c',
    'core/compiler.c',
    'core/debug.c',
    'core/math.c',
    'core/memory.c',
    'core/object.c',
    'core/scanner.c',
    'core/table.c',
    'core/value.c',
    'core/vm.c',
]

external_sources = [
    'external/crossline.c',
]

emo_sources = files(cli_sources, core_sources, external_sources)

emo_deps = []

executable('emo', emo_sources,
  include_directories : incdir,
  dependencies: emo_deps,
  install: true,
)
