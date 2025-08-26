.env template:
# ---- Auth ----
HUGGING_FACE_HUB_TOKEN=

# ---- vLLM - Chat (LLM behavior) ----
VLLM_CHAT_MODEL=TinyLlama/TinyLlama-1.1B-Chat-v1.0
VLLM_CHAT_DTYPE=auto
VLLM_CHAT_GPU_UTIL=0.70
VLLM_CHAT_MAX_MODEL_LEN=2048


# ---- vLLM - Embeddings (embedder behavior) ----
VLLM_EMBED_MODEL=nomic-ai/nomic-embed-text-v1
VLLM_EMBED_DTYPE=auto
VLLM_EMBED_GPU_UTIL=0.70

# ---- MinIO (not using yet but keeping here as a reminder for later) ----
# MINIO_ROOT_USER=
# MINIO_ROOT_PASSWORD=

# ---- Optional: tweak without editing YAML ----
QDRANT_URI=http://qdrant:6333
WEBUI_NAME=Adam's Local LLM 8GbVRAM 64GbMemory


