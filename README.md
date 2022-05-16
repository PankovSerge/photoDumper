# photoDumper
Application downloads album photos from VK

![photo_2022-05-13_21-30-47](https://user-images.githubusercontent.com/833157/168378024-1f67e441-507c-4a43-8613-17e9a145d252.jpg)


## Download page
[go to Download page](https://github.com/Gasoid/photoDumper/releases)


### Features:
- oauth2
- exif metadata: dateTime, GPS coordinates
- download all albums
- download a particular album

### Static files
- `tar xvfp <(curl -sL https://github.com/Gasoid/photoDumper/releases/download/1.0.0/build.zip)`
- or `go generate staticAssets.go`

### Run:
```bash
go run ./
```

## API Docs (swagger routines)
Regenerate docs:
```bash
swag init
```

Format swagger comments:
```bash
swag fmt
```

## Known issues
- albums with the same name will not be downloaded
- use `ulimit -n 1024` in order to fix 'too many open files' issue


### Tags
- скачать все альбомы с вконтакте без регистрации и смс
- скачать фото с вк бесплатно
- приложение для скачивания всех фото из вк
