docker build -t zayro/car-service .

docker run -p 4000:4000 -d zayro/car-service

# delete image

- docker rmi -f zayro/car-service