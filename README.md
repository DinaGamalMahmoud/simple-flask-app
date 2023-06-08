# simple-flask-app
## This is Simple Flask App

### Use APP
> Install the requirments

```pip install -r requirements.txt```

> Run the App

```flask run -p <port-number>```

### Use Docker Image
> Build Docker Image

```docker build  -t <image-name>:<tag> . ```

> Run the Image

```docker run --name <container-name>  -i -p <port-number>:<port-number> <image-name>:<tag>```
