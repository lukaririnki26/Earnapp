# Earnapp
echo -n sdk-node- && head -c 1024 /dev/urandom | md5sum | tr -d ' -'

docker run -d --restart always -m 64M --network host -e TZ=Asia/Jakarta --log-opt max-size=1m --log-opt max-file=1 --name  earn1 -e EARNAPP_UUID= madereddy/earnapp
