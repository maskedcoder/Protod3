# PROTOD3 - Protobuf's metadata extractor

A python3 port of PROTOD that was written for python2 with some cosmetic improvments.


## What is PROTOD?

Protod is a tool able to extract Google's protobuf metadata from any binary
file. This version has been designed to cover every file format.

The goal of this tool is to recover serialized protobuf's metadata inserted
at compilation time inside an executable, and to make it available as .proto
file, ready to compile with protoc (protobuf's compiler).

For further information on Google's protobuf library, please see:

https://developers.google.com/protocol-buffers/docs/overview


## How to use this tool?

Its usage is very simple. Here is a sample:
To extract every metadata file (.proto) from a given executable:
```bash
$ python protod.py somebinary
```

## Is this tool limited?

Current version does not support every kind of fields, we are aware of this.
It was developed as a proof-of-concept to demonstrate this technique, and of
course you are more than welcome to contribute !

Feel free to fork this project on Github, and let us know about your issues
and ideas !


## THANKS

Great thanks to UNclePecos for his time, and all the Sysdream's staff for
their support.
