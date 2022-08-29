# Joseph Supples OpSwat MetaDefender File Hash Lookup and Upload
Run via
> node src/index.js

## Description
The program looks to see if the hash calculated via CrytoJS is present in OpSwat. 
If it is, the data_id is returned and it continues to look up and print to console the analysis results. 
If it is not, then it is uploaded, the OpSwat hash is stored and then continues to print to console the analysis results. 
The program then does a hash lookup with the newly stored OpSwat hash as a proof of the lookup hash functionality and prints the results again. 

## How to Use

Run via
> node src/index.js

This uses an API key generated from MetaDefender to access the public API. Generate your own API key and store it in a .env file in the root directory. The file used for this demonstration is stored as 'sample.txt' in the root directory. If you would like to use a different sample file, update the filePath field.  

