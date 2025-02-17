FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /use/share/nginx/html/index.html
# this onbuild instructions runs only, when any user uses your image
ONBUILD COPY index.html /use/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]