FROM node:alpine
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
COPY . /usr/app
COPY ./.env /usr/app
EXPOSE 4000
CMD ["npm", "run", "start"]



#Рабочий код
# FROM node:alpine
# WORKDIR /usr/app
# COPY ./package.json ./
# RUN npm install
# COPY . /usr/app
# COPY ./.env /usr/app
# EXPOSE 4000
# CMD ["npm", "run", "start"]