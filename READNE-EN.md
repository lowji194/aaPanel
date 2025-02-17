[![🇻🇳 Tiếng Việt](https://img.shields.io/badge/Ngôn_ngữ-Tiếng_Việt-red?style=for-the-badge&logo=Google%20Translate)](README.md)
---
# How to Install and Activate aaPanel

## Introduction

**aaPanel** is an open source web hosting control panel that helps you easily manage your server with an intuitive user interface. The following guide will help you install **aaPanel** and activate the **Premium** version with powerful features.

## Prerequisites

- **Operating System**: Ubuntu, CentOS, or Debian.

- **Root Access**: You need root access to your server.

- **Internet Connection**: Make sure your server has a stable internet connection to download the necessary packages.

## Step 1: Install aaPanel

1. **Access the server**:

- Use SSH to log in to your server:

```bash
ssh root@<server_ip_address>

```

2. **Install aaPanel**:

- Run the following command to download and install **aaPanel** from GitHub:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/lowji194/linh-tinh/refs/heads/main/AAPanel/aapanel_7.sh)

```

- The above command will download the script from GitHub and automatically install **aaPanel** on your server. This process may take a few minutes.

3. **Confirm Installation**:

- After successful installation, you will receive login information and server IP address to access **aaPanel**.

## Step 2: Access aaPanel

1. **Open web browser**:

- After installation, open browser and enter server IP address and port `8888`:

```
http://<server_ip_address>:8888
```

- For example: `http://192.168.1.100:8888`

2. **Login**:

- Use the login information provided during installation to log in to **aaPanel**.

- Sample login information:

- **Account**: admin

- **Password**: (password provided in the post-installation notification)

- After successfully logging in, you will see the **aaPanel** management interface.

## Step 3: Activate aaPanel Premium

1. **Run the Premium** activation command:

- To upgrade to the **Premium** version of aaPanel, you need to run the following command:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/lowji194/linh-tinh/refs/heads/main/AAPanel/Active7.sh)
```

- This command will activate **aaPanel Premium**, giving you more advanced features such as support for many management features, security and system optimization.

2. **Check activation success**:

- After running the activation command, you can check the Premium version in the **aaPanel** interface. The Premium version will provide more options and powerful server management features.

## Step 4: Additional configuration (Optional)

After installing and activating **aaPanel**, you can configure additional services such as:

- **Web Server installation**: Apache, Nginx or OpenLiteSpeed.

- **PHP and MySQL installation**: aaPanel supports installation and configuration of PHP and MySQL versions.

- **SSL installation**: Install free SSL from Let's Encrypt to secure your website.

- **Firewall and security configuration**: aaPanel supports firewall configuration and advanced security features.

## Note

- **Access**: Make sure you are using root or sudo account on your server to perform the above steps.

- **Firewall**: If you are having trouble accessing aaPanel, check your server firewall configuration, make sure port `8888` is open for external connections.

- **Ensure stable internet connection**: The installation and activation process may require downloading packages from the internet, so make sure your server has a good internet connection.
