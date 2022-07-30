# A Detailed Description of Ports

 
SMB is a client-server approach.  This means that the client makes specific requests and the server responds accordingly.
Once it is connected, it will allow a user to make requests to a file server.  A file server might have resources like printer sharing mail slots and named pipes on the remote server.  Named pipes are a way to send your data without having any sort of performance issues involving a network stack.

Barry Feigenbaum who at the time worked for IBM designed the first SMB. Then Microsoft wanted to rename it to CIFS which added more features like allowing for larger file size. CIFS is just a specific implementation of SMB.

Samba, which we used today in class, is an open-source implementation of SMB

Open ports are necessary to communicate across the Internet. However, an open port can become a security risk when the service listening to the port is misconfigured, unpatched, vulnerable to exploits, or has poor network security rules.