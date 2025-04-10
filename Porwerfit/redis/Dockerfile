FROM redis:6.2-alpine

# Copia o arquivo de configuração personalizado para dentro do container
COPY redis.conf /usr/local/etc/redis/redis.conf

# Comando para iniciar o Redis com a configuração customizada
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
