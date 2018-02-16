# QuixBugs generator

Tests generator of buggy and correct Java programs from QuixBugs:
[QuixBugs](https://github.com/jkoppel/QuixBugs/)

## Generated test cases

[Tests that execute buggy programs](/src/main/java/java_programs_test)

[Tests that execute correct programs](/src/main/java/correct_java_programs_test)

## Usage of Generation tool.

### Generating testing of buggy version

run: ``junit_test_generator.QuixBugsTestGenerator``

### Generating testing of correct version

run: ``junit_test_generator.QuixBugsTestGenerator -programpackage correct_java_programs -testpackage correct_java_programs_test```



### Arguments:

rootdir: path to the root dir where sources of buggy programs are found

testdestination: path to the folder where tests will be written

programpackage: package name of the programs under analysis

testpackage: package name of the generated 	tests

onefolderperprogram: each tests goes in a separate folder
	