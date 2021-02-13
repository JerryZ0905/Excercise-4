docker build --tag my-python-app .
docker rm -f python-app (ONLY DO THIS IF LINE 3 got error)
docker run --name python-app -p 5000:5000 my-python-app python /app/index.py Jerry
