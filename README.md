add one of these commands in command line

-fV input_file_name output_file_name (Vertical Flip of image)
-fH input_file_name output_file_name (Horizontal Flip of image)
-rRn input_file_name output_file_name (Rotation Right n*90 degrees),n: an integer
-rLn input_file_name output_file_name (Rotation Left n*90 degrees),n: an integer
-n input_file_name output_file_name (to add salt-pepper noise)


Attention!!!::  input_file_name + output_file_name without .pgm ending!
 
Try lena.pgm using the commands below...


 ////////////////////////////////////////////
-fV lena lenaout                          //
-rL2 lena lenaout ( 2*90 = 180 degrees)  //
-n lena lenanoise                       //
/////////////////////////////////////////
