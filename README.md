# One Review

A global place for all product reviews

https://www.youtube.com/watch?v=yQtgY4VG3kM&ab_channel=AmichaiMantinband

docker build -t one-review-youtube .

docker image ls | grep -i youtube

docker run -p 5001:5001 --name one-review-api-youtube one-review-youtube
