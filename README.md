# sublime_javac_src
sublime text java build compiler
optimation class and package


# project structur

    |- ProjectRoot
    |______|- bin
    |______|- src


# usage
- add file build system in sublimeText package directory
- edit cmd path in build system to spesific path when you save javac_src.exe
  
        "cmd": ["D:\\JC\\Dev\\Eclipse\\__javarun\\javac_src"],
	      "working_dir": "${file_path}",

- create folder root project in sublimeText
- create child folder src -> 'default sources directory'

# Main
- default MainActivity is Main.java | ex: com.test.Main
- or you can set costum MainActivity in <b>setting.jc</b> file

# recomended
- install package javaIME via package controll to autocomplate
- enjoy code
