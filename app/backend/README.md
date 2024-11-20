# Backend Application Documentation

## Overview

This document provides an overview of the backend application, including its functionality, the technologies used, and how to set it up and run it.

## Technologies Used

- Python
- Quart
- Azure SDKs

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.9 or higher
- Azure CLI
- Node.js (for frontend dependencies)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/azure-search-openai-demo.git
    cd azure-search-openai-demo
    ```

2. Set up a Python virtual environment:
    ```sh
    python3 -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install backend dependencies:
    ```sh
    pip install -r app/backend/requirements.txt
    ```

4. Install frontend dependencies:
    ```sh
    cd app/frontend
    npm install
    cd ../../
    ```

### Running the Application

1. Start the backend server:
    ```sh
    cd app
    ./start.sh  # On Windows use `./start.ps1`
    ```

2. The backend server should now be running on `http://localhost:50505`.

### Running Tests

To run the tests, use the following command:
```sh
pytest