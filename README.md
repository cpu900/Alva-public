# 🛡️ Welcome to AlvaLabs Security Skills Test
---
Follow the instructions below to clone the repository and run the Docker containers.

## 🖥️ Getting Started

### ✅ Prerequisites

If you already have Docker and Git installed, you can skip to the next step.

#### For Windows users:
- To install Docker, visit the [Docker Desktop for Windows download page](https://www.docker.com/products/docker-desktop).
- To install Git, you can download it from the [Git for Windows download page](https://git-scm.com/download/win).

  
#### For macOS users:
- To install Docker, visit the [Docker Desktop for Mac download page](https://www.docker.com/products/docker-desktop).
- To install Git, you can use [Homebrew](https://brew.sh/) with the following command:
  ```bash
  brew install git
  ```


---

## 📥 Download the docker-compose file

You can either clone the entire repository using Git or download just the `docker-compose.yml` file.

### Option 1: Clone the repository

```bash
git clone https://github.com/cpu900/Alva-public.git
cd Alva-public
```

### Option 2: Download `docker-compose.yml` manually

1. Go to the `docker-compose.yml` file in the github repo.
2. Select **Download raw file**, and save it in a directory on your computer.

---

## ▶️ Run the Containers

In the directory where `docker-compose.yml` is located, run:

```bash
docker-compose up
```

This will start the services defined in the file. You can now access the test at [http://localhost](http://localhost) in your web browser.

---

## 🧪 Shutdown and Remove Files

When you're done with your testing, you can stop and remove the containers by running:

```bash
docker-compose down
```

If you also want to delete the downloaded images and free up disk space:

```bash
docker image rm cpu900/acmecorp-alva:1.5 cpu900/buggy-alva:1.5
```

> ⚠️ Only do this if you no longer need the containers and have finished the tests.
