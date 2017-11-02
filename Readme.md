# ClientRG
- a perl-based client interaction system

## usage
use "make interactive" to connect to the server (assuming it is running)

```bash
% make
perl tl.pl
Enter server Address: localhost
Enter port: 5071
usec 10000 
Try to open socket
Open
```

run the hubServer in 'Tools' to host the system (use q to quit system)

```bash
% cd Tool
Tool/ % perl hubServer.pl :(
hubServer[0]> o
hubServer[0]> Open Complete
hubServer[1]> 
```

run a client to communicate with the  client system

```bash
% cd Tool
% perl hubClient.pl
Client [0]> o 5072
```

and send the system commands via that other client.
