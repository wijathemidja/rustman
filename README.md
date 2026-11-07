As of right now Rustman 2 is broken for some strings, i believe it is multi-line only. Something happened with multi-line integration and/or space integration that messed up, v weird as it worked before hand on my test strings. 
Will fix eventually, but for now the project will be archived. Rustman was mainly for learning some basic Rust, which I did. 

# rustman

A huffman encoder built in rust

# Features

## Encoding Text

To encode a string use:

rman encode "Example Text" ex

To encode a file use:

rman encode "example.txt" ex

## Decoding Text

To decode an rmt use:

rman decode ex

## Converting Rustman Compressed Text

If you have Rustman compressed text files from an older version of Rustman use:

rman convert txt ex

If you want old Rustman versions to be able to decode your text use:

rman convert rmt ex

NOTE : If converting RMTs to TXT the message MUST BE one line.

If you have a Rustman 1 RMT that you want to be able to decode use:

rustman convert legacy ex

If you have a Rustman 2 RMT that you want Rustman 1 to be able to decode use:

rustman convert rm1 ex



