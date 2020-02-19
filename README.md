Contest parsing tool
=================

This is a python script that parses the sample tests from the contest problem pages. For each problem, it generates the sample input/output files and a shell script to run sample tests. It uses urllib and HTMLparser. (works only for Codeforces)


./parse.py id

Where `512` is the contest number, not the round number! Check the URL of the contest on your browser, that is the number you are supposed to use.

