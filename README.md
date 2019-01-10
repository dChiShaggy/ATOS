# ATOS
Rockwell SINT ASCII to String AIO

This AIO was compiled in V28 of Logix Designer.

It takes a SINT that has a ASCII code and then converts it to a String


INPUT [SINT]
   Tag containing code to convert to string
   
   
OUTPUT [String]
    Returns the single charater String for the code provide in the Input
    
    
EXAMPLE
    Input = 65
    Ouput = 'A'
    
    Input = 6A
    Output = 'j'
    
This AOI will also convert the special characters supported by the PLC
    $t  Tab
    $l  Line Feed
    $f  Form Feed
    $r  Carriage Return
