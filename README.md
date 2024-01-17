# test-docker-kpp

Test docker image for KPP

## 0. Clone

```
git clone https://github.com/KarloPry/test-docker-kpp
cd test-docker-kpp
```

## 1. Build

```
docker build -t test-docker-kpp .
```

## 2. Run

```
docker run -d -p 3000:3000 test-docker-kpp
```

## 3. Test

```
curl http://localhost:3000
```

## 4. Stop

```
docker ps
docker stop <container_id>
```
