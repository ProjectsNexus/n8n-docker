
FROM n8nio/n8n:latest

# n8n internal web server
ENV N8N_PORT=5678
ENV N8N_LISTEN_ADDRESS=0.0.0.0

# Reverse proxy
ENV N8N_PROXY_HOPS=1
ENV N8N_PROTOCOL=http

# Timezone
ENV GENERIC_TIMEZONE=Asia/Karachi
ENV TZ=Asia/Karachi

EXPOSE 5678
