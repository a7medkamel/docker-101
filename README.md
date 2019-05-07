# Docker 101

## Lesson #1 - Command Line App
```
docker build . -t a
```

```
docker run a
```

## Lesson #2 - Web Server
```
docker build -f example/Dockerfile_web . -t b
```

```
docker run -it -p 80:80 b
```

## Lesson #3 - TypeScript Web Server
```
docker build -f example/Dockerfile_ts . -t c
```

```
docker run -it -p 80:80 c
```

## Lesson #4 - TypeScript Web Server / Cleaner
```
docker build -f example/Dockerfile_ts_2 . -t d
```

```
docker run -it -p 80:80 d
```

## Lesson #5 - Multi Stage Build
```
docker build -f example/Dockerfile_ms . -t e
```

```
docker run -it -p 80:80 e
```
