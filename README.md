# StratosCMS

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: In Development](https://img.shields.io/badge/status-in%20development-orange)](https://github.com/YOUR_USERNAME/stratos-cms)

A modern, flexible, and "plug-and-play" modular Headless CMS designed to be easily integrated into any web project.

## 🚀 About The Project

**StratosCMS** was born out of the need to eliminate repetitive work when starting new projects that require a content management system. The core philosophy is to provide a lightweight core system that can be extended with independent modules, like Lego blocks, to build the exact functionality needed.

* **Headless:** Serves your content through a REST API.
* **Modular:** Only include the features you need (e.g., Blog, Gallery) for your project.
* **Flexible Content Modeling:** Dynamically create your own content types and fields directly from the admin panel.

### 🛠️ Built With

* **Backend:** Node.js, Express.js
* **Database:** PostgreSQL
* **Frontend:** React, TypeScript
* **Styling:** Tailwind CSS
* **Containerization:** Docker, Docker Compose

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* [Node.js](https://nodejs.org/en/)
* [Docker](https://www.docker.com/products/docker-desktop/)

### Installation

1.  **Clone the repo**
    ```sh
    git clone [https://github.com/trcnvrl/StratosCMS.git](https://github.com/trcnvrl/StratosCMS.git)
    cd stratos-cms
    ```

2.  **Create an Environment File**
    Create a new file named `.env` in the root directory by copying the example file. Fill in the necessary values.
    ```sh
    cp .env.example .env
    ```

3.  **Start Docker Containers**
    This command will start the PostgreSQL database in the background.
    ```sh
    docker-compose up -d
    ```

4.  **Install Backend Dependencies**
    ```sh
    # Navigate to the backend source directory if needed
    npm install
    ```

5.  **Run the Backend Server**
    ```sh
    npm start
    ```
    The server will start by default at `http://localhost:3000`.

## 📂 Project Structure
├── src/
│   ├── api/          # API Routes
│   ├── config/       # Configuration files (db, etc.)
│   └── modules/      # Plug-and-play modules
├── .env              # Environment variables
├── docker-compose.yml # Docker service definitions
└── package.json

## 🗺️ Roadmap

* [x] Core System and Database Architecture
* [ ] User Management and Authentication (JWT)
* [ ] Dynamic Content Type Builder (Content Modeling)
* [ ] Develop **Blog Module**
* [ ] Develop **Page Management Module**
* [ ] Admin Panel UI with React

## 📜 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 📞 Contact

Tarcan Vural - [@trcnvrl](https://twitter.com/trcnvrl) - tarcanvural@gmail.com 

Project Link: [https://github.com/YOUR_USERNAME/stratos-cms](https://github.com/trcnvrl/StratosCMS)
