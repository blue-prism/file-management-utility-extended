# Utility - File Management [Extended C#]
Common utility for file IO...exposing actions not accommodated by the Blue Prism Utility - File Management object. Specifically, this utility includes the following functionality:

## Actions
* Delete Files
  * Delete all files in a single directory, delete all files recursively under that directory, target files for deletion based on file extension pattern(s), target files for deletion based on age, and remove any directories left empty 
* Download File As Binary
  * Download a file from the provided url and return it to the caller as a binary file
* Download File to Disk
  * Download a file from the provided url and save it to the give folder path
* Parse Fixed Width File to Collection
  * Parse a fixed width file based on a given record definition of field names, start positions, and lengths

## Language
* All code stages written in **C#**
