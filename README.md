 #Russ DDos
Target sites can see in
https://ddosmonitor.herokuapp.com/

### Requirments
`Node (v17.6.0)`
`Docker Docker Compoose`
`Linux, Mac or WSL 2 (avaliability to run bash scripts)` 

### Script for setup in Digital Ocean (Docker container)
`
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash &&
source ~/.bashrc &&
nvm install 17 &&
nvm use 17 &&
git clone https://github.com/SergeyGuliy/russ_ddos_2.git &&
cd russ_ddos_2/ &&
npm run startLog
`