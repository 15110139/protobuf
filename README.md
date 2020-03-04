# protobuf - Repository contain proto file all system

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

# Features!

 #### Protocol buffers is (are?) an Interface Definition Language and serialization library:
- You define your data structures in its IDL i.e. describe the data objects you want to use
- It provides routines to translate your data objects to and from binary, e.g. for writing/reading data from disk
 #### gRPC uses the same IDL but adds syntax "rpc" which lets you define Remote Procedure Call method signatures using the Protobuf data structures as data types:
- You define your data structures
- You add your rpc method definitions
- It provides code to serve up and call the method signatures over a network
- You can still serialize the data objects manually with Protobuf if you need to
 ### When you communicate between gRPC server you must have proto file .
# Reference
 -  [Protocol-buffers](https://developers.google.com/protocol-buffers/docs/overview) Welcome to the developer documentation for protocol buffers – a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more.
 - [Proto3](https://developers.google.com/protocol-buffers/docs/proto3) This guide describes how to use the protocol buffer language to structure your protocol buffer data, including .proto file syntax and how to generate data access classes from your .proto files.
 