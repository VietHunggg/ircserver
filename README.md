# Quick Start
0. Compile all servers and client
```
chmod +x compile_all.sh
./compile_all.sh
```
1. Start the encryption server
```
./enc.server
```
2. Start the IRC server
```
./irc.server
```
3. Start another IRC server and connect to the first one
```
./irc.server 8785 localhost 8784
```
4. Start a client, connect to the first IRC server
```
./client
```
5. Start another client, connect to the second IRC server
```
./client localhost 8785
```
6. Start sending messages