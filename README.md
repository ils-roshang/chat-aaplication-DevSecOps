# Realtime Chat Application

A full-stack realtime chat application built with React, Node.js, Socket.io, and Docker.

## 🚀 Features

- **Realtime Messaging**: Instant message delivery using WebSockets.
- **Room Support**: Join and chat in specific rooms.
- **Dockerized**: Fully containerized for easy deployment and development.

## 🛠️ Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express, Socket.io
- **Infrastructure**: Docker, Docker Compose

## 🏁 Getting Started

### Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop) installed on your machine.

### Installation & Run

1. **Clone the repository** (if you haven't already):
   git clone https://github.com/ils-roshang/chat-aaplication-DevSecOps.git
   cd chat-aaplication-DevSecOps

2. **Start the application**:
   docker-compose up -d --build

3. **Access the app**:
   - **Client**: Open [http://localhost:3000](http://localhost:3000) in your browser.
   - **Server**: Running on [http://localhost:5000](http://localhost:5000).

## 🛑 Stopping the App

To stop the containers:

docker-compose down

