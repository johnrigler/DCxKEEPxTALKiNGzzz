# DCxKEEPxTALKiNGzzz
This project will involve using one single python script called unspendable.
You can download it at https://github.com/johnrigler/unspendable.git

I also have some bash function that I use. I tend to work with a tool
which I developed called ALP. I also use this name to refer to a 
sort of universal ledger project where folks can craft their own genesis block
and thus create a clone of their favorite ledger.

Here I render a broadcast stream into format that can be transformed into a digibyte
transaction. All of the data is encapsulated into a set of bash functions which
spits out a valid digibyte transaction. Because the transaction order will get mixed up,
we must spend a number of characters on ordering the message.

Thus the unspendable command must be used to create a special set of prefix rules:

The first character is always D, the prefix always ends with x
The second character is the "speaker" or "voice"
Satoshi Codes are used to represent line position.

The transaction writes to digibyte production network.
