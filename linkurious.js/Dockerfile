FROM node:0.10
EXPOSE 8000
RUN git clone git://github.com/Linkurious/linkurious.js.git
WORKDIR linkurious.js
RUN npm install
RUN npm run build
RUN mkdir /app
RUN ln -s /app
CMD ["npm", "start"]
