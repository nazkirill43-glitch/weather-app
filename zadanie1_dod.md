# Zadanie 1 - Część Nieobowiązkowa: Opcja 1 (Adaptacja)

## Multi-platform Build - Docker Build

Ze względu na problemy z siecią (CloudFront), użyto standardowego docker build.
![alt text](image-3.png)

---

## Polecenia Użyte

### 1. Budowanie Obrazu

docker build -t nazkirill43-glitch/weather-app:latest .
![alt text](image-4.png)

#### 2. Push na DockerHub

docker push nazkirill43-glitch/weather-app:latest

#### 3. Sprawdzenie Obrazu

docker images | findstr weather-app
![alt text](image-5.png)
