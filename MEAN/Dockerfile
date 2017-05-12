FROM bitnami/node:7

RUN install_packages libkrb5-dev

COPY app-code /app

RUN chown -R bitnami:bitnami /app /home/bitnami 

USER bitnami
WORKDIR /app

RUN npm install 

CMD ["npm", "start"] 
