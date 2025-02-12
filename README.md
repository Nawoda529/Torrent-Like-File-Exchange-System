# 📁 Torrent-Like File Exchange System  

A high-performance **multi-client** file exchange system built using **C and socket programming**, simulating a simplified **torrent-like file sharing** environment. This project enables seamless **file transfers** between a central **server** and multiple **clients**, handling **100+ simultaneous connections** efficiently with **multi-processing**.  

## 🚀 Features  

✅ **Multi-Client Support** – Handles **100+ clients concurrently** using multi-processing.  
✅ **File Request & Transfer** – Clients can **browse, select, and download** files from the server.  
✅ **Chunk-Based Downloading** – Files are transferred in **1024-byte chunks** for efficiency.  
✅ **Supports All File Types** – Text, images, videos, executables – everything works!  
✅ **Real-Time Progress Bar** – Clients get a **live download progress bar** for tracking.  
✅ **Logging & Monitoring** – The server logs **IP addresses, timestamps, requested files, and transfer statuses**.  

## ⚙️ How It Works  

1️⃣ **The Server** listens on a specified IP/port and maintains a directory of **50+ downloadable files**.  
2️⃣ **Clients** connect, request a file list, and choose a file to download.  
3️⃣ The server **sends the file in chunks** while logging each transaction.  
4️⃣ The client **receives and reassembles** the file while displaying a **progress bar**.  

## 🛠️ Setup  

🔹 **Compile the Server**  
```bash
gcc server.c -o server
./server
```  
🔹 **Compile the Client**  
```bash
gcc client.c -o client
./client
```  

## 🔥 Why This Project?  

💡 **Scalable** – Supports **hundreds of concurrent downloads**.  
💡 **Efficient** – Uses **multi-processing** for performance optimization.  
💡 **Real-World Learning** – Covers **networking, sockets, file handling, and system-level programming**.  

### 🌍 Contribute & Improve  
Fork, clone, and explore! Future enhancements could include **encryption, parallel downloads, and checksum verification**. 🚀  

📌 **Perfect for students & developers diving into socket programming!** 🎯
