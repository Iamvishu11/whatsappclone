FROM mhart/alpine-node:7.6.0

# Add app source files
ADD src /src

WORKDIR /src

#install node modules
RUN npm install
RUN axios install
RUN bluebird install
RUN body-parser install
RUN cookie-parser install
RUN express install
RUN path install
RUN request-promise install
RUN save install

CMD ["node", "app.js"]
