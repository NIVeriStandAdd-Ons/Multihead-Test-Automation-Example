## Multihead Test Automation Example ##

This is an exmaple of how to use a single target within NI VeriStand to automate multiple UUTs independantly. It allows for maintaining a single set of test files that are automatically modified per individual UUT test station.

### LabVIEW Version ###

LabVIEW 2015

### Built Availability ###

Users are allowed to build anything under Build Specifications in the source's LabVIEW project(s). Pre-built versions are available upon request through NI Field Sales.

### Quality, Limitations ###

IP has been tested by developer. It is currently being tested with customers.

Automation is meant for a basic cycle tester.  It has a custom initialization and shutdown sequence.  The main sequence is just playing a CSV over and over for a set number of iterations.

### Dependencies ###

AMC 3.3.0.21
GXML 1.4.2.8
OpenG Data Libraries 4.2.0.21

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
