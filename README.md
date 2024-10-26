# GitHub Repository Dashboard

This project is a **GitHub Repository Dashboard** that allows users to view statistics and details of any GitHub repository by entering its URL. The project uses a **React-based frontend** with **TailwindCSS** for styling, and a **Ballerina backend** to fetch repository data from GitHub API.

## Features

- Display repository statistics such as **Stars**, **Watchers**, **Forks**, **Open Issues**, and **Size**.
- Shows repository details including **Name**, **Visibility**, **Creation Date**, **Last Update**, and **Default Branch**.
- Toggle between **Light** and **Dark** themes.
- Validate GitHub URLs and handle API errors.
- Backend service using **Ballerina** to handle GitHub API requests.

## Tech Stack

- **Frontend**: HTML, TailwindCSS, JavaScript with Vite.
- **Backend**: Ballerina.
- **API**: GitHub REST API.

## Getting Started

### Prerequisites

- **Node.js** (for frontend)
- **Ballerina** (for backend)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/repository-dashboard.git
    cd repository-dashboard
    ```

2. **Frontend Setup**:
    - Navigate to the `frontend` folder:
        ```bash
        cd frontend
        ```
    - Install dependencies:
        ```bash
        npm install
        ```
    - Run the frontend development server:
        ```bash
        npm run dev
        ```
    - The frontend will be served at `http://localhost:3000`.

3. **Backend Setup**:
    - Navigate to the `backend` folder:
        ```bash
        cd backend
        ```
    - Run the Ballerina service:
        ```bash
        bal run
        ```
    - The backend service will listen on `http://localhost:8080`.

## Usage

1. Open the frontend at `http://localhost:3000`.
2. Enter the GitHub repository URL in the input field and click **Search**.
3. The dashboard will fetch and display repository statistics and details.
4. Toggle between light and dark mode using the button at the top.

## Example

- **Repository URL**: `https://github.com/ballerina-platform/ballerina-lang`
- **Fetched Stats**: Stars, Watchers, Forks, Open Issues, Size, and more.

## Project Structure

```bash
repository-dashboard/
│
├── backend/
│   └── main.bal       # Ballerina service
│
├── frontend/
│   └── index.html     # Frontend HTML & TailwindCSS
│   └── vite.config.js # Vite configuration
│
└── README.md          # Project documentation
