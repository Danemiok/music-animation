## Code file Docker file
- Use official nginx image:

        FROM nginx:alpine

- Copy your project to nginx folder:

        COPY . /usr/share/nginx/html

- Port:

        EXPOSE 80


## Command 
- Make sure you’re logged in:

        docker login
- Build Docker image

        docker build -t username .

- To test locally:

        docker run -d -p username