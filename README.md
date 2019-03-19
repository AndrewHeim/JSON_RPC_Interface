# JSON_RPC_Interface
A module to interface with DCAF tags using JSON RPC.


DEPENDENCIES:

 - the Open-G libraries from VI Package Manager

 - This module depends on this library:
[JSON-RPC Server Framework](https://github.com/NISystemsEngineering/JSONRPC)

 - And that one depends depends on this library:

[JSON support for LabVIEW](https://github.com/tannerblair/JSON-Support-for-LabVIEW)



Internal builds of these are available on the file share server.	Use the latest version of the JSON lib:   ni_lib_json-3.0.1.71
	(I had to remove a non-RT compatible VI, and if you use the older version then you'll get a broken NI on RT.	)