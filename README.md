# Docker 101

## Lesson #1 - Command Line App
```
docker build . -t cli
```

```
docker run cli
```

## Lesson #2 - Web Server
```
docker build -f example/Dockerfile_web . -t web
```

```
docker run -it -p 80:80 web
```

```
ctrl + c

```

## Lesson #3 - TypeScript Web Server
```
docker build -f example/Dockerfile_ts . -t web_ts
```

```
docker run -it -p 80:80 web_ts
```

```
ctrl + c

```

## Lesson #4 - TypeScript Web Server / Cleaner
```
docker build -f example/Dockerfile_ts_2 . -t web_ts2
```

```
docker run -it -p 80:80 web_ts2
```

```
ctrl + c

```

## Lesson #5 - Multi Stage Build
```
docker build -f example/Dockerfile_ms . -t web_ts_ms
```

```
docker run -it -p 80:80 web_ts_ms
```

```
ctrl + c

```
