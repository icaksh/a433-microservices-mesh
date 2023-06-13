# import node v14 on alpine
FROM node:14-alpine

# deklarasikan workdir ke /app
WORKDIR /app

# copy semua file ke workdir
COPY . .

# deklarasi environtment yang dibutuhkan
ENV PORT=3000

# install dependencies yang dibutuhkan
RUN npm install --production --unsafe-perm

# expose port 3000
EXPOSE 3000

# run npm start jika kontainer diluncurkan
CMD ["npm","start"]