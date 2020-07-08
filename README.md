glanchat
====

A LAN chatting program in python based on goodwill. It does not need a special
server setup. Install on clients and just run. glanchat is based on lanchat with graphical interface. Only tested on python3.x


Things you should know
----------------------

- No selecting a server( finds it on it's own)
- New server selected if current goes down
- Printing is wierd ( Can someone help me fix it?)
- No encryption (boo)
- No protection against DOS
- Picks your username from the shell (you can use any username uing --name )
- It's **pseudo-distributed** . It actually uses a server-client model of communication
  but does so in a manner that everyone just ends up seeing the client.

**Note** : In case the chat does not run check that you are allowed to do UDP broadcast on the network.


Install
-------

```
$ git clone https://github.com/shudwi/glanchat 
$ python3 -m glanchat
```

How to use
----------

```
$ python3 -m glanchat
$ python3 -m glanchat --version
$ python3 -m glanchat -c
$ python3 -m glanchat -a 'notify-send LANCHAT_message'
$ python3 -m glanchat -n 'username'
```

