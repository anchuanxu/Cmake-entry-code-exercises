project (hello)
set(src_list main.c)
message (status " this is binary dir" ${hello_binary_dir})
message (status " this is source dir" ${hello_source_dir})
add_executable(hello ${src_list})
