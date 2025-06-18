#cifuzz:build-template:begin
#add_fuzz_test({{ .FuzzTestName }} {{ .FileName }})
#target_link_libraries(fuzz PRIVATE wolfssl)
#cifuzz:build-template:end
