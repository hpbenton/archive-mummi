# Mummichog Archival

This is code to run the archival mummichog code.

First clone the repository with

``` bash
 git clone http://git-metabocode.scripps.edu:3000/XCMSOnline/mummichog-archival ~/mummichogArchival
```
Normally, mummichog version >2.0 is installed via pip install mummichog. However, archival code has not yet been 
uploaded to a online based repository. Consequently, users who want to run the command line version will need to run 
the following 

```bash
 pip install mummichogArchival --user
```
From here you should be able to run

```bash
 mummichogArchival -f inputfolder 
```
Where the input folder has either tsv or txt files of the data.

## ToDo
* Make into web interface - flask



