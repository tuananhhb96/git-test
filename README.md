dockerFile : anhbt14.Dockerfile
Command tạo network : docker network create --driver bridge --subnet 10.10.20.0/24  bridgexxx
Command tạo container : docker build -f ./anhbt14.Dockerfile -t webapp:1.0  .
