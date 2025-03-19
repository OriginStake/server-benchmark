# Server Benchmark 🚀  

**A simple and powerful tool to test server performance, network speed, and disk I/O.**  

![Result](https://raw.githubusercontent.com/OriginStake/server-benchmark/refs/heads/main/server-benchmark.png)

----



## 🛠 How to Use  

### 1. **Run the Script Directly**  
Use this command to run the benchmark and save the results to a file:  
```bash
curl -Lso- https://raw.githubusercontent.com/OriginStake/server-benchmark/main/server-benchmark.sh | bash
```
This will:  
- Run the benchmark.  

## 📊 What It Tests  

- **System Info**: CPU model, cores, RAM, disk usage, OS, and uptime.  
- **Network Speed**: Download speed from multiple global servers.  
- **Disk Performance**: Read/write speed using `dd` and `fio`.  


----



## ⚠️ Notes  

- **Run as root**: The script requires root privileges.  
If you’re not root, use `sudo`:  
sudo bash server-benchmark.sh  
- **Always review scripts**: Check the script before running it.  


----
