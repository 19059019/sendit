![sendit logo](sendit.png)

# RW354 Project2 -  Reliable Blast User Datagram Protocol (RBUDP)

## Group Members:

Michael John Shepherd   - 19059019 at sun dot ac dot za

Martin William von Fintel       - 20058837 at sun dot ac dot za

## File Contents:

The **SourceCode** folder contains the Netbeans project that holds all of the
java files that are used in this project. This includes SenderPane.java and RecieverPane.java There is also a *Makefile* in the **src**
folder that will compile the needed files and *run_sender* and *run_receiver*
shell files to run the server and the client.

**Executables** contains executable jar files for the receiver and the sender.

**Report** contains the project report, as well as all of the test results, images and resources used to create the report.

## Usage:

The application can be used by navigating to the **Executables** folder and executing the sender and receiver jar files in that order. this can be done as follows:

```
java -jar Sender.jar
java -jar Receiver.jar
```

Note that if the jar file states that it is not executable, then you will need to run the
following command in the terminal, in the **Executables** directory before
it will be allowed to run:

```
chmod +x Sender.jar
chmod +x Receiver.jar
```
