# crackpkcs8

I needed to check a dictionary of passwords for a certificate. Linear approach was insufficient, so I modified a thread ready program from http://sourceforge.net/projects/crackpkcs12/ or https://github.com/crackpkcs12/crackpkcs12/

Compile:

gcc crackpkcs8.c -o crackpkcs8 -lssl -lcrypto -lpthread

Note: You would need libssl-dev as requirement to compile

