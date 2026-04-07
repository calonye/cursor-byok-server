## Cursor Byok API Server

cursor-byok-server is the server for Cursor Assistant's Pro mode. It supports an unlimited number of tabs and byok, and allows for custom API usage with Cursor.

#### Prerequisites and Principles

The principle is to forward the traffic of 'Cursor tab' and 'Cursor Agent' to the official service through a **token with byok qualification**.

The 'Cursor Agent' enforces byok, and you must implement specific features in the client forwarding and provide private model configuration information to allow passage through the agent service.

- [Bilibili Homepage](https://space.bilibili.com/311706663)

- [Client (not open source)](https://dcne38qm5vlg.feishu.cn/wiki/YGaWw1ejXiiJ8EkismtcoIYUnNd)

#### Note

This service is for the server forwarding of a mode within Cursor Assistant. The core capability of Cursor Assistant lies in the **local mode**, and this service serves as a temporary intermediate solution. When the **local mode** becomes production-ready, this service will be deprecated.

#### Building and Deployment

- It is recommended to build and deploy using Docker only.

## Star History

<a href="https://www.star-history.com/?repos=leookun%2Fcursor-byok-server&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=leookun/cursor-byok-server&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=leookun/cursor-byok-server&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=leookun/cursor-byok-server&type=date&legend=top-left" />
 </picture>
</a>
