# Instructions:
1. Have Docker installed
2. Clone this repo
   ```git clone https://github.com/mclaramarinho/vue-docker-app.git```
3. Go into the folder vue-docker-app
4. Build the container image
  ```docker build -t vue-docker-image```
  It might take a while to install package.json.
6. Run the container:
  ```docker run -it -p 8080:80 -rm vue-docker-image```
7. Open the following location on the browser:
  ```localhost:8080```
