# Docker 安装指南

通过 GitHub Actions 从官网抓取 Docker 的安装脚本。

## 安装方式

### 1. 使用官方安装脚本（可能不可用）
#### 从官网获取官方脚本并执行以安装 Docker：  

```bash
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```
### 2. 使用release抓取的脚本（推荐）
#### 从release获取官方脚本并执行以安装 Docker：  

```bash
curl -fsSL https://github.com/FujiiTaki/docker-install/releases/latest/download/linux.sh -o linux.sh
chmod +x linux.sh
sudo ./linux.sh
```
#### 添加代理版本（适用于网络访问受限的环境）：

##### [代理发布页](https://ghproxy.link/),如当前代理地址不可用获取最新代理地址替换 https://ghgo.xyz/
```bash
curl -fsSL https://ghgo.xyz/https://github.com/FujiiTaki/docker-install/releases/latest/download/linux.sh -o linux.sh
chmod +x linux.sh
sudo ./linux.sh
```
### 3. 桌面版本安装包
#### 详见[release](https://github.com/FujiiTaki/docker-install/releases/tag/latest)
