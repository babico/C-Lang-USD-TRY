# C-USD-TRY
%99 Stack Overflow  
%1  Me  

## A little note for compiling  
1-  Install curl to MinGW.  
2-  Download [here](https://curl.haxx.se/docs/sslcerts.html) the SSL certificate for curl. They must be in the same file with source code.   
3-  Compile with the code below.  
    ```C
      gcc .\dolar-try-converter-online.c -o .\dolar-try-converter-online.exe -lcurl -L C:\MinGW\lib
    ```
