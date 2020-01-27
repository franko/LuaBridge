project('LuaBridge', 'cpp', version: '2.4.1', default_options : 'cpp_std=c++11')

subdir('Source')

pkg = import('pkgconfig')

pkg.generate([],
    filebase : 'luabridge',
    name : 'LuaBridge',
    description : 'The LuaBridge library',
    url : 'https://github.com/vinniefalco/LuaBridge',
)
