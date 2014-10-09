This is a fork of the [gmock](https://code.google.com/p/googlemock/)
project with modest edits for bundling in an existing CMake project.

Usage
-----
I wanted to be able to bundle `gmock` like so:

1. Clone it as a subdirectory.
2. In CMakeLists.txt, add the subdirectory. Then, I should be able to:

        include_directories(${gmock_INCLUDE_DIRS})
        ...
        target_link_libraries(my_app gmock)
3. Use `gmock` at your will. See the project site for [detailed documentation](https://code.google.com/p/gmock/w/list).

License
-----
[BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause).
