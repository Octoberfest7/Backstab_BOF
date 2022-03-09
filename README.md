# Backstab_BOF
This is a Beacon Object File implementation of Yaxser's Backstab for use with Cobalt Strike. 
![image](https://user-images.githubusercontent.com/91164728/157537763-684a4b2c-b677-40ea-af22-33e7fe5bb81d.png)

# Changes
A few changes were made to the code during the port of the original:

  1. The ProcExp driver is no longer stored/loaded as a resource, it is a hardcoded byte array in resource.c

  2. There were several memory leaks in the original code that I found and resolved


# Credits
  1. First and foremost, Yaxser and his cool tool: https://github.com/Yaxser/Backstab

  2. Trustedsec for his CS-Situational-Awareness-BOF repo which was a huge help during the porting process.  I used snippets of his code in this project and I highly recommend anyone who is getting into writing BOF's check the repo out: https://github.com/trustedsec/CS-Situational-Awareness-BOF
