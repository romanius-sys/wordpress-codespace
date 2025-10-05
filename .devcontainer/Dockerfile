# Dockerfile for devcontainer
FROM wordpress:latest

# Встановлюємо Git
RUN apt-get update && apt-get install -y git && rm -rf /var/lib/apt/lists/*

# Створюємо користувача codespace
ARG USERNAME=codespace
RUN useradd -m -s /bin/bash $USERNAME
USER $USERNAME
