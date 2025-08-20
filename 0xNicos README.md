# Introduction

# ⚡️ Pipe Firestarter

**Pipe Firestarter** is a decentralized storage and delivery network — think of it as a blockchain-powered alternative to **Google Drive + Cloudflare**.  
Instead of relying on a single company, it distributes files across **independent nodes**, making data **faster, safer, and censorship-resistant**.

---

## 🚀 Key Features
- Built on **Solana**.
- Already stores **1 petabyte** of Solana’s blockchain history.
- Cuts **validator sync times** by ~30%.
- Upload files or folders with optional **end-to-end encryption**.
- Global content delivery with **low latency**.
- **Community-powered infrastructure** instead of corporations.

---

## 💰 Payments & Tokenomics
- Payments are made in **$PIPE tokens** (Devnet).  
- **1 PIPE ≈ 1 GB** of storage.  
- When tokens are **burned for storage**, they are **re-minted** and rewarded to **node operators**.  
- Incentivizes a sustainable ecosystem where the **community runs the infrastructure**.

---

## 🌍 Why Firestarter?
Firestarter provides developers and users with a **full-stack decentralized alternative** for:
- **Storage**  
- **CDN (Content Delivery Network)**  
- **Edge compute**  

✅ All at a fraction of the cost compared to traditional providers.


# Pre-Requirements

## Install All Require Dependecies

```
sudo apt update && sudo apt upgrade -y 
```
```
sudo apt install curl iptables build-essential git wget lz4 jq make gcc postgresql-client nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev tar clang bsdmainutils ncdu unzip libleveldb-dev libclang-dev ninja-build -y
```

## Install rustup
```
curl https://sh.rustup.rs -sSf | sh
```
```
source $HOME/.cargo/env
```
Check version
```
rustc --version
cargo --version
```

## Installation

### Clone the Repo
```
git clone https://github.com/PipeNetwork/pipe.git
cd pipe
```
### Install pipe-cli
```
cargo install --path .
```
### Verify The Installation
```
pipe -h
```
### Set-Up a User
```
pipe new-user <your_username>
```
``` Replace <your_username> with your: ```

``` Save Solana Pubkey: ```

### Set-Up Your Password
```
pipe set-password
```
``` Enter a Strong PASS: ```

### Save Your Credentials
``` Open the file and save all the credentials in it: ```
```
nano ~/.pipe-cli.json
```

## Basic CLI's Operations
### Referral Campaign
``` You'll earn up to 100 PIPE for every referral who swap at least 1 SOL DEVNET for PIPE ```
#### Enter the Refer Code:
```
pipe referral apply NICOS-KR3G
```
#### Get Your referral code:
```
pipe referral generate
```
#### Check your referral stats
```
pipe referral show
```
### Swap Sol (Devnet) to Pipe
Get Sol Devnet Faucet from here

Swap

```
pipe  swap-sol-for-pipe <AMOUNT_SOL>
```
``` Swap minimum 1sol to pipe ```
### Upload a File
```
pipe upload-file <FILE_PATH> <FILE_NAME>
```
  ```Replace <FILE_PATH> & <FILE_NAME> with their actual:```

  ```Dont upload any confidential file (Wallet keys & personal docs)```

  ```You can upload any videos or large file too:```

  ```For home path, use:```
```
~/Name_of_your_file
```
### Create Public Link
``` We will create the public link of our uploaded file: ```
```
pipe create-public-link <FILE_NAME>
```
 ``` Replace <FILE_NAME> which you have used earlier while uploading a file:```

<img width="945" height="672" alt="pipe2" src="https://github.com/user-attachments/assets/5e08ec32-6407-40fb-94c5-2a296d10c913" />

### Check Token-Usage
 ``` You can get to know about the usage of the pipe devnet tokens, after uploading and Downloading Files: ``` 
 ```
pipe token-usage
```
### Many CLI's Operations are there in pipe, So you can read and apply from pipe's official Repo: [repo](https://github.com/PipeNetwork/pipe)

## Using VPS

You can transfer files between your local device and your VPS using **SFTP** in Termius.

### Step: Drag & Drop (Easy)
1. Open Termius and connect to your VPS.
2. In the left panel, click on **SFTP**.
3. You’ll see two panels:
   - **Left** → your local files.
   - **Right** → your VPS files.
4. Drag and drop files between the panels to upload or download.

## Using VPS on Mobile (Termius App)

You can upload files from your phone to your VPS using the **SFTP feature** in Termius.

### Steps
1. Open the **Termius app** on your phone.
2. At the top, you will see your **Local Device** (in green).
3. Tap on **SFTP** at the bottom of the screen.
4. Tap on **Local** (at the top) to view your phone’s files.
5. Then tap on the **Host side** (your VPS).
6. On the Local side (your phone), tap on any folder — this will redirect you to your phone’s **file explorer**.
7. Select the file or folder you want to upload.
8. It will redirect you back to Termius.
9. Tap the **three dots (⋮)** at the top-right corner and select **Transfer**.
10. The file will now be sent to your VPS.

> 📱 This method works for both single files and whole folders.


							 
# Get Firestarter Role
``` join pipe discord ``` [join pipe discord](https://discord.gg/uzxDBxEb)

##Role Requirement👇

<img width="1705" height="497" alt="image" src="https://github.com/user-attachments/assets/c1b3f1d3-7973-4471-90b0-d042f2794e40" />

### Upload Your File from [here](https://github.com/psalmsprint/Pipe-Firestarter-Storage-Node/new/main?readme=1#upload-a-file)
### Get public link of your upload files from [here](https://github.com/psalmsprint/Pipe-Firestarter-Storage-Node/new/main?readme=1#create-public-link)
Done✔️


If you have any issue open an issue on this repo or Dm me on [x](x.com/0xNicos)

Thank you!
