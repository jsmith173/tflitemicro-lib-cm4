Device: Stm32 F429 zi<br />
Need to compile in a special way<br />
* compile to a library (.a, C++)
* Stm32CubeIDE: library project
	* C and C++ include path: tensorflow rootdir at the first place other tensorflow include directories not to add
	* C and C++ include path: add the third_party dir-s
	* CFLAGS: ISO C99
	* CPPFLAGS: ISO C++11
* Project files only, source come from tflitemicro-ren-src, drag and drop the Src folder to Stm32CubeIDE project
