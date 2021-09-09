# QuickUnzip
The library written in Java helps reduce the time taken to extract the files out of a zip file. 

The libray has shown to reduce the time spent during extraction of a zip file by a great extent. Numbers below                                                   
Zip Files smaller than 1 GB   -   40%-45% improvement                                                                                                             
Zip Files larger than 1 GB    -   95%-103% improvement

Dependencies:                                                                                                                                                     
commons-compress-1.1x.jar or higher                                                                                                                             

Sample Program 1:                                                                                                                                                            
QuickUnzip unzipper = new QuickUnzip();                                                                                                                        
unzipper.extract("/Users/john/Test.zip");

Sample Program 2:                                                                                                                                                           
QuickUnzip unzipper = new QuickUnzip();                                                                                                                        
unzipper.extract("/Users/john/Test.zip", "/Users/john/backup/Test");
