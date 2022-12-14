# blockchain_21224960
Blockchain project
\
Clone from github - https://github.com/kuroashisanji/blockchain_21224960.git 

Build an image: docker build -t kuroashisanji/21224960sanji:smartcontract .

Run an image - docker run -p 8090:8080 --name smartcontract -d kuroashisanji/21224960sanji:smartcontract


docker push kuroashisanji/21224960sanji:smartcontract


ETH TRASNSFER: - 
curl --header "Content-Type: application/json" --request POST --data '{"address":"0x42442147D273EaC997EA77217C9E5C170434FF7D","amount":"0.005"}' http://localhost:8090/eth



TOKEN TRANSFER: - 
curl --header "Content-Type: application/json" --request POST --data '{"address":"0x42442147D273EaC997EA77217C9E5C170434FF7D"}' http://localhost:8090/token



