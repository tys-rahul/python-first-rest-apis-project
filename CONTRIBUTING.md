# CONTRIBUTING

## How to run the Dockerfile locally

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run"
<!-- docker run -dp 5000:5000 -w //app -v "$(pwd):/app" image_name sh -c "flask run" -->

```
