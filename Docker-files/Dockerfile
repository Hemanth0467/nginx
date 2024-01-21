FROM nginx:latest
RUN apt update && apt install git -y
RUN git clone -b test https://github.com/Hemanth0467/nginx.git
RUN cd nginx
COPY . /usr/share/nginx/html
