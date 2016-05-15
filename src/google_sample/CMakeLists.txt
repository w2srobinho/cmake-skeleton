
project(google_sample)


set(HEADER_FILES
    sample1.h
)

set(SOURCE_FILES
    sample1.cc
)

add_library(google_sample
    ${SOURCE_FILES} 
    ${HEADER_FILES}
)
