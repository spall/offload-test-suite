add_offloadtest_tool(offloader
              offloader.cpp)

target_link_libraries(offloader PRIVATE
                      LLVMSupport
                      OffloadTestAPI
                      OffloadTestImage
                      OffloadTestSupport)
