# for paddle test case

if(WITH_TESTING)
  add_library(paddle_test_main STATIC TestMain.cpp)
  add_dependencies(paddle_test_main gen_proto_cpp)
endif()
