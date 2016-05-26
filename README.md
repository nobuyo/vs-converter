# vs-settings-generator

This script generates setting files of Microsoft VisualStudio semi-automatically, to reproduces the directory structure of the solution.
* sln
* vcxproj
* vcxproj.filters


## Notes
* In order to obtain the use of the script, or the exact configuration file, you will need to rewrite those files manually.  
e.g. On project include settings, you must change source file name, and include file(s).
* Script obtains GUID from online (require Internet connection).
* Supported Only C++ project.
* Some files(etc/orig.*) requied sepalately.
