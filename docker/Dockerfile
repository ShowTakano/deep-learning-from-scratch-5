FROM nvcr.io/nvidia/pytorch:26.04-py3

WORKDIR /workspace

# Keep logs unbuffered and make matplotlib usable in headless containers.
ENV PYTHONUNBUFFERED=1 \
    MPLBACKEND=Agg

RUN mkdir -p /deep-learning-from-scratch-5
