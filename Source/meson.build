luabridge_root_headers = [
    'LuaBridge/List.h',
    'LuaBridge/LuaBridge.h',
    'LuaBridge/Map.h',
    'LuaBridge/RefCountedObject.h',
    'LuaBridge/RefCountedPtr.h',
    'LuaBridge/UnorderedMap.h',
    'LuaBridge/Vector.h',
]

luabridge_detail_headers = [
    'LuaBridge/detail/CFunctions.h',
    'LuaBridge/detail/ClassInfo.h',
    'LuaBridge/detail/Config.h',
    'LuaBridge/detail/Constructor.h',
    'LuaBridge/detail/dump.h',
    'LuaBridge/detail/FuncTraits.h',
    'LuaBridge/detail/Iterator.h',
    'LuaBridge/detail/LuaException.h',
    'LuaBridge/detail/LuaHelpers.h',
    'LuaBridge/detail/LuaRef.h',
    'LuaBridge/detail/Namespace.h',
    'LuaBridge/detail/Security.h',
    'LuaBridge/detail/Stack.h',
    'LuaBridge/detail/TypeList.h',
    'LuaBridge/detail/TypeTraits.h',
    'LuaBridge/detail/Userdata.h',
]

foreach header_file : luabridge_root_headers
    install_headers(header_file, subdir: 'LuaBridge')
endforeach

foreach header_file : luabridge_detail_headers
    install_headers(header_file, subdir: 'LuaBridge/detail')
endforeach
