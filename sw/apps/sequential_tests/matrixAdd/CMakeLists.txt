add_application(matrixAdd32 matrixAdd.c LABELS "sequential_tests" FLAGS "-DWORD=32" SUBDIR "matrixAdd32")
add_application(matrixAdd16 matrixAdd.c LABELS "sequential_tests" FLAGS "-DWORD=16" SUBDIR "matrixAdd16")
add_application(matrixAdd8  matrixAdd.c LABELS "sequential_tests" FLAGS "-DWORD=8"  SUBDIR "matrixAdd8")
