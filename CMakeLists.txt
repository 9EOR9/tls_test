PROJECT(test_tls C)

ADD_EXECUTABLE(test_tls ${CMAKE_SOURCE_DIR}/schannel.c ${CMAKE_SOURCE_DIR}/certs.c)
