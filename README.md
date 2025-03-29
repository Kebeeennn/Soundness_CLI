Soundness Testnet Registration

Generate Your Key here: 
sudo apt update
sudo apt upgrade 
type -y
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
source ~/.bashrc
soundnessup install
soundnessup update
soundness-cli generate-key --name my-key
To view your seedphrase: 
soundness-cli export-key --name my-key
