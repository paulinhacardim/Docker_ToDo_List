FROM node:14-alpine
EXPOSE 3001 
WORKDIR /app
ADD  node_modules.tar.gz ./
COPY ./ /app
COPY . . 
RUN npm install
ENTRYPOINT ["npm"]
CMD ["start"]


