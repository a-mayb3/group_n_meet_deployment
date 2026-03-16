# group_n_meet
This project and its submodules and components are distributed publicly under the AGPLv3.
- [a-mayb3/group_n_meet_deployment (this repository)](https://github.com/a-mayb3/group_n_meet_backend)
- [a-mayb3/group_n_meet_backend](https://github.com/a-mayb3/group_n_meet_backend)
- [a-mayb3/group_n_meet_flutter (to be developed and released still)]()
> These repositories will (eventually) also be available on https://git.vollex.cc/
## How to run
This project is meant to be run on Linux but can be run under other OS with Docker support (like MSWin or MACOS).
### On Linux/*nix:
#### Requirements
- git / GitHub CLI / GitHub Desktop 
- docker / docker engine / docker desktop
#### Steps
1. Clone the repo
```bash
git clone --depth=1 git@github.com:a-mayb3/group_n_meet_deployment.git group_n_meet
cd group_n_meet
```
or
```bash
gh repo clone a-mayb3/group_n_meet_deployment ./group_n_meet -- --depth=1
cd group_n_meet
```

2. Get the submodules
```bash
git submodule update --init --recursive
```

3. Run
```bash
docker compose up -d # or docker-compose up -d
```
