# fake-firebase
fake firebase to locally fake firebase for testing or playing.

## Synopsis
the Fake firebase relies on JSON loaded from base file names "sample_db.ffb"
shopuld have possibility save the JSON to sample_db after some editing is done. 

## Motivation
for example for testing purposes, when the connection is limitted or the test case requirements exeeds the free account posibilities

## Code Example
var ref = new FakeFirebase('sample_db');

the rest of functionality copies Firebase

## License
MIT
