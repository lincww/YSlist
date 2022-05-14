# YSList
> *Another file list program for sharing and uploads*
> 
> *Inspired by [Alist](https://github.com/Xhofe/alist)*
---
## Features
- [ ] List and download files with multi provider
  - [ ] Local disk
  - [ ] Aliyun OSS
  - [ ] TencentCloud COS
  - [ ] S3-like object storages
  - [ ] WebDAV
  - [ ] OneDrive
  - [ ] Web3.storage
- [ ] Uploads
  - [ ] Login required
  - [ ] Pending list
  - [ ] Size limit
- [ ] Account system
   - [ ] Third-party OAuth
- [ ] Multi Database support
  - [ ] SQLite
  
## Deploy
The project requires a `python3` environment.

We recommend using SQLite as the database. However, to the requirements of deploying on serverless services, it's able to use remote databases.

Please visit [wiki]() for details.

## Development
1. Clone project
2. Create a virtualEnv. `python -m venv venv`
3. Create `config.toml` by `config.toml.sample`
4. Install requirements. `pip install -r requirements.txt`
Visit [wiki]() for more.