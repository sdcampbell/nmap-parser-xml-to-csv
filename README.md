### Script for parsing nmap xml output to csv format
	This script is originate by Didier Stevens and modified by Sumedt Jitpukdebodin
### Version
- 0.1
		- Change some display and fix the bug of parser multiple ports and hosts
- 0.2
		- Rearrange columns and add end time column into output csv.

### How to use
1. Normal usage for display result
./nmap-xml-script-output-modify.py test.xml
2. Change default delimiter(;) to ,
./nmap-xml-script-output-modify.py test.xml -s ,
3. Output to test.csv
./nmap-xml-script-output-modify.py test.xml -s , -o test.csv
