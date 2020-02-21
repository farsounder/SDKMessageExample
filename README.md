# Minimal SDK Example
## Example implementation - SonaSoft™ SDK message passing
This example implements both methods of commumicating with SonaSoft via the API described in [FarSounder's SDK documentation:](http://www.farsounder.com/files/F33583-FarSounder_IDD_4.0.1.pdf)
1. Publish / Subscribe
2. Request / Reply

The compiled versions of the `proto-files` are already included in the project, however if needed they can be compiled using the included version of the protoc.exe proto compiler. The necessary binaries for ZeroMQ are also included. However if you would like to download either of these dependencies, they can be found here:
* ZeroMQ - https://zeromq.org/
* ProtocolBuffers - https://developers.google.com/protocol-buffers

We use ProtocolBuffers to manage structured data in a language neutral way, and ZeroMQ to pass serialized "proto" messages between processes.

If you have any questions, suggestions, or recommendations, please feel free to open an issue on this repo or to email: service@farsounder.com.