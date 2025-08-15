FROM python:3.11-slim

WORKDIR /app

# Copy only the compiled challenge artifact
COPY grader.pyc /app/grader.pyc

# Ensure consistent stdout/stderr behavior
ENV PYTHONDONTWRITEBYTECODE=1 \
    PYTHONUNBUFFERED=1

# Default command runs the grader
ENTRYPOINT ["python", "/app/grader.pyc"]


