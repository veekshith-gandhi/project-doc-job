# 🐳 What is Docker?

## Docker is a tool that helps developers build, ship, and run applications in small, isolated environments called containers.

### Think of a container like a lightweight, portable box that includes:

- Your app
- All its code
- Its dependencies (Node.js, Python, Java, etc.)
- Even parts of the OS it needs


# 🚪 Docker Port Mapping (`-p`)

## What is Port Mapping?

By default, a Docker container is isolated from your host machine.  
To access services running inside a container (like a web server), you need to **map ports** from the container to your local system.

---

## 🔧 Syntax

```bash
docker run -p <host_port>:<container_port> <image>
```
---