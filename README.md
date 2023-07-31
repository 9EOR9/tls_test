Example for TLS v1.3 crash, using the schannel example code from https://gist.github.com/mmozeiko/c0dfcc8fec527a90a02145d2cc0bfb6d.

  Usage: test_tls client-cert.pem client-key.pem

  The example connects to db4free.net MySQL server, sends the CLIENT_SSL capability flag and starts a TLS handshake.

Requirements: 
- Windows build >= 20348
- Visual Studio
- CMake

Build:
mkdir bld
cd bld
cmake ..
# Start VS
test_tls.sln
