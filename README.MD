## Instructions

1. Install

Streamlit docs:
https://docs.streamlit.io/library/get-started/installation

```
pip install -r requirements.txt
```

2. Run

```
streamlit run main.py
```

## Run in Docker container

1. Build Docker image

```
docker build --tag katanaml/sparrow-ui .
```

2. Run Docker container

```
docker run -it --name sparrow-ui -p 7860:7860 katanaml/sparrow-ui:latest
```
