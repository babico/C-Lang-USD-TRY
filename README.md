# C-USD-TRY
%99 Stack Overflow  
%1  Me  

## A little note for compiling  
1-  Install [curl](https://curl.se/windows/) to MinGW.  
2-  Download [here](https://curl.haxx.se/docs/sslcerts.html) the SSL certificate for curl. They must be in the same file with source code and rename it as 'cacert.pem'.

3-  Compile with the code below.  
    ```
      gcc .\dolar-try-converter-online.c -o .\dolar-try-converter-online.exe -lcurl -L C:\MinGW\lib
    ```
