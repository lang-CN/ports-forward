# ports-forward
端口转发

sudo apt install socat
socat TCP4-LISTEN:443,reuseaddr,fork TCP4:www.google.com:443


gh codespace ports forward <remote-port>:<local-port>...
gh cs ports forward 5900:443


