# Nginx  
NGINX (pronounced **Engine-X**) is a high-performance **web server** that can also act as a:

- Reverse Proxy
- Load Balancer
- API Gateway
- Caching Server
- Mail Proxy
- Media/Streaming Server

It is widely used for large-scale, high-traffic applications due to its **asynchronous, event-driven architecture**.

---

## 🚀 Why NGINX is Fast?

| Apache | NGINX |
|-------|-------|
| Creates **1 thread per request** | Uses **event-driven worker processes** |
| Heavy CPU + RAM usage at scale | Handles thousands of connections efficiently |
| Slower on high concurrent traffic | Ideal for **high performance websites** |

**NGINX = Non-Blocking + Asynchronous + Lightweight + Scalable**

---

## 🛠 Installation

### Ubuntu / Debian
```bash
sudo apt update
sudo apt install nginx


-rw-r--r-- 1 root root 1.5K Nov 30  2023 nginx.conf

