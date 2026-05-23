# group_n_meet
This project and its submodules and components are distributed publicly under the AGPLv3.
- [a-mayb3/group_n_meet_deployment (this repository)](https://github.com/a-mayb3/group_n_meet_deployment)
- [a-mayb3/group_n_meet_backend](https://github.com/a-mayb3/group_n_meet_backend)
- [a-mayb3/group_n_meet_angular](https://github.com/a-mayb3/group_n_meet_angular)
> [!IMPORTANT]
> These repositories will eventually be migrated on https://git.vollex.cc/.
> Everything else left here will be marked as a Public Archive.
## How to run
> [!NOTE]
> This project is meant to be run on Linux but can be run under other OS with Docker support (like MSWin or MACOS).
### On Linux/*nix:
#### Requirements
- git / GitHub CLI / GitHub Desktop
- docker / docker engine / docker desktop
- docker compose / docker-compose
#### Steps
##### 1. Clone the repo
```bash
git clone --depth=1 git@github.com:a-mayb3/group_n_meet_deployment.git group_n_meet
cd group_n_meet
```
or using GitHub CLI
```bash
gh repo clone a-mayb3/group_n_meet_deployment ./group_n_meet -- --depth=1
cd group_n_meet
```
##### 2. Get the submodules
```bash
git submodule update --init --recursive
```
##### 3. Run
```bash
docker compose up -d # or docker-compose up -d
```
