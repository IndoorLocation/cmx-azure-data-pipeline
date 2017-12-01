FROM node:9.2.0

RUN git clone https://github.com/IndoorLocation/cmx-socket-indoor-location-emitter cmx

WORKDIR /cmx

RUN npm install

ENTRYPOINT [ "npm", "run", "start-listener" ]