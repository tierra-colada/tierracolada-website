# tierracolada-website

Start server with the command:
```
hugo server -F --cleanDestinationDir
```

To clean build and upload use (to build with about pages you need to add -FD flags):
```
hugo -F --cleanDestinationDir
```

Upload to yc:
```
aws --endpoint-url=https://storage.yandexcloud.net/ s3 cp --recursive D:/dev/tierracolada-website/public/ s3://tierracolada.ru
```