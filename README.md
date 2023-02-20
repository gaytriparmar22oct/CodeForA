
# Perfromance Test Assignment
â€¢	Functional Requirements
o       	API: https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false 

o	Test Data: (Category ID: 6327, 6328, 6329, 6330, 6331, 6332, 6333, 6334, 6335, 6336)
o	Test Assertion:

ï‚§	Check for the Response Status
On a successful response, validate the response with below criteria:

ï‚§	Parameter Check: Category ID
Text Check: "CanRelist": true

o	Print following values in a csv file: Category ID, Name, Path, Promotion ID, Price

ï‚§	Please print all Promotion IDs and respective Prices per Category ID





## How To Run it

Follow below things

1. Add path for data outcome into Beanshell sampler code

Example

File file =new File ("<YourPath>\\SampledataFromBeanShellDataSampler.csv");

2. Add CSV Config data set file path into the project

3. To Run in Non GUI Mode ,Please follow below Command

Jmeter -n -t <path of Jmx file> -l <Path of the output file>

