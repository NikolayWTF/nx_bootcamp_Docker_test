FROM python:3

RUN python3 -m pip install "pelican[markdown]"


FROM nginx

COPY output /usr/share/nginx/html
