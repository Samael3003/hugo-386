+++
author = "Sahil Sawant"
title = "I don't know what I did"
date = "2022-11-16"
description = "> I really don't know what happened..."
tags = [
    "",
]
categories = [
    "",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++

# Hello Friend.

Today what happened with me was truly unbelieveable. I was programming my **EDI Project**. 
The thing is, I have never been able to sit and program for more than 15-20 minuits.
But, today was different. I have surpassed all my previous limits and continuously programmed for a total of 5:43 hrs.
Well, it was not all programming, obviously. I had to refer various sources on Internet to read the Documentationa and stuff.

## > My EDI Project. : )   ___ _Phase-I_

So, my friend, let me explain my Project and steps I took to accompalish it until its' completion.

First-of-all, I have prepared a Server-Client Interface in my "FEATHERS", that is my Laptop. The "Server" here, is an ideal server in listening mode.
The Client, on other hand is in Active mode. The Client is made to throw three files to the Server. To note here, is that both CLIENT and the SERVER are supposed to be on same IP-address and Port (here,- localhost 4444)
Now, the client throws the Information of three different sources. - 
    1. System Information.
    2. Process Information.
    3. Network Information.
    
Now, the Server accepts the request and packs up the information in three files, named upon the port numbers.
The difference between the byte-transfer can tell us the information passed from certain port.
The server then names the packed information with the lable of ***.xyz***. The thing to note here is that the file is not in readable format.
So, we use the program **ANALYSER.PY** to convert it into some readable format and with ***.csv*** extension, so we get the Tabular form.

SO, we now we get 3 files namely- **Sysinfo.csv, Procinfo.csv, Netinfo.csv**. Out of these, the **Sysinfo.csv** provides the information about all the System Configuration, like the _cpu architecture_, _ram present_, _Operationg System_, _Kernel Information_, etc.
The **Procinfo.csv** provides the information about the _ProcessID_, _Process-Name_, _Process Status_. 
The **Netinfo.csv** provides the information about the _ProcessID_, _Local IP & Port_, _Remote IP & Port_.
