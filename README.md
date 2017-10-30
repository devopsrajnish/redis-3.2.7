To build redis image run below command

docker build -t redis:3.2.7 -f redis.dockerfile .

To run redis container in interactive mode run below command

docker run -p 6381:6379 -t redis:3.2.7

To run redis container in background run below command

docker run -p 6381:6379 -t redis:3.2.7 -d
