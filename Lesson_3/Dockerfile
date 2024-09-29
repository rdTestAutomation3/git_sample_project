# Docker Image'ınızın temelini seçin
FROM ubuntu:20.04

# Yapılandırmaları ve bağımlılıkları tanımlayın
RUN apt-get update
RUN apt-get install -y python3

# Uygulama kodunu ekleyin
COPY .. /app
WORKDIR /app

# Çalıştırılabilir komutu belirtin
CMD ["python3", "app.py"]