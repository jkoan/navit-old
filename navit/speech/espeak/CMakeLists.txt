module_add_library(speech_espeak speech-espeak speak.c)
target_link_libraries(speech_espeak support_espeak)
