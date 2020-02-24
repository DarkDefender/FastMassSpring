eigen = dependency('eigen3')
glm = dependency('glm')
glew = dependency('glew')
freeglut = dependency('freeglut')
openmesh = dependency('openmesh')

deps = [eigen, glm, glew, freeglut, openmesh]

src = ['app.cpp', 'MassSpringSolver.cpp', 'Mesh.cpp', 'Renderer.cpp', 'Shader.cpp', 'UserInteraction.cpp']

exe = executable('demo', src, dependencies : deps)

test('simple test', exe)
