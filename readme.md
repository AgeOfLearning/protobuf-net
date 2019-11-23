# Protobuf-net: AofL Fork

This is a fork of Protobuf.NET library used by Age of Learning.

`academy` branch continues release `r668` with the following fixes:

1. Removed forward slash `/` from the list of supported leading characters for arguments, to support unix-style paths
2. Precompiled does NOT fail anymore if .NET Framework version can't be detected
3. Added support for generic types serialization.


See also: [Protobuf.NET Documentation](https://github.com/protobuf-net/protobuf-net/blob/master/README.md)
