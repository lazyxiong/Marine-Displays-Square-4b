FROM python:3.11-slim

RUN apt-get update && \
    apt-get install -y git curl nodejs npm && \
    pip install --no-cache-dir platformio && \
    npm install -g @google/gemini-cli && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
