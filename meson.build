project('glutess', 'c')

src = [
    'src/dict.c',
    'src/geom.c',
    'src/memalloc.c',
    'src/mesh.c',
    'src/normal.c',
    'src/priorityq.c',
    'src/priorityq-heap.c',
    'src/render.c',
    'src/sweep.c',
    'src/tess.c',
    'src/tessellate.c',
    'src/tessmono.c'
]

incdir = include_directories('include')

glutess = static_library('glutess', src, include_directories: incdir)
glutess_dep = declare_dependency(link_with: glutess, include_directories: incdir)