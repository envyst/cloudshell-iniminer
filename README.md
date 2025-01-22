# INI Miner Setup Guide

This guide explains how to set up and run the INI Miner on a Linux machine.

## Prerequisites
- A Linux-based operating system
- `wget` installed on your system

---

## Steps to Set Up and Run the Miner

### 1. Clone the Repository or Download the Scripts
Download the necessary Bash scripts or clone this repository (if applicable).
```bash
git clone https://github.com/envyst/cloudshell-iniminer.git
cd cloudshell-iniminer
chmod +x download_and_prepare.sh run_miner.sh
```

---

### 2. Prepare the Environment

Run the `download_and_prepare.sh` script to download the miner and set the correct permissions.

```bash
./download_and_prepare.sh
```

---

### 3. Run Mine

Edit run_miner.sh, on part **address** and **Worker001**.
```bash
vim run_miner.sh
```
- press 'i'
- edit address/worker
- press esc
```bash
:wq
```
- enter

Run the `run_miner.sh` script to start mining.

```bash
./run_miner.sh
```

---

### 4. Cloudshell Reconnected
just run the miner
```bash
./run_miner.sh
```
