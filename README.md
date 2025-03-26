# Multithreading_Chat_App

This is a simple **multithreaded chatroom** implemented in **C** using **sockets and pthreads**.  
Multiple clients can connect to a server and exchange messages in real time.

##  Features
- **Multi-client support** using threads.
- **Real-time messaging** between clients.
- **Thread synchronization** using `pthread_mutex_t`.
- **Graceful exit** when a client disconnects.

---

##  Installation & Setup

### **Compile the Server and Client**
Open a terminal and run:

```sh
gcc server.c -o server -pthread
gcc client.c -o client -pthread
