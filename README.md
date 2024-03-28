# Simple Load Balancer

**Description:** This project implements a basic load balancer using Go. It distributes incoming traffic across multiple backend servers using a Round Robin strategy.

## Features
- **Round Robin Selection:** Requests are evenly distributed among backend servers.
- **Health Monitoring:** The load balancer continuously monitors backend server health.

## How it Works
- **Define Backend Servers:** Specify backend servers and their URLs.
- **Initialize Load Balancer:** Create an instance with the list of backend servers.
- **Start Load Balancer:** Launch the load balancer server to begin routing requests.
