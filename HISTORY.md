# History

- Version 1.0.2, unreleased*
	- Bugfixed the inclusion of files; at a point, some files were included multiple times, even if the masterscript said include_once. This bug was fixed by storing the realpath of all included files
- Version 1.0.1, unreleased*
	- Bugfixed the usage of $mergeScripts: by now, only scripts identified as PHP scripts get included (extension must be .php)
- Version 1.0.0, released on 2012-11-21
	- Added the method getGhostFunctions, which will return all unused -- but defined -- functions in a script
- Version 0.0.4, released on 2102-11-21
	- Bugfixed the inclusion of subscripts within subscripts (path problem)
	- Added a testcase for dynamic file inclusion
- Version 0.0.3, released on 2012-11-21
	- Removed cli support (yet untested)
	- Removed inclusion of composer autoloader from src/JuggleCode.php
- Version 0.0.2, released on 2012-10-12
	- Added mergeFile method
- Version 0.0.1, released on 2012-09-14
	- Bugfixed oppressFunctionCall
- Version 0.0.0 released on 2012-09-12

*unreleased versions are not provided as packagist/github tags, therefore need to be included via "dev-master"
