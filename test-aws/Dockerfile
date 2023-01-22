FROM node:lts-alpine
ENV NODE_ENV=production
ENV PORT=80
WORKDIR /app
COPY . .
RUN npm install --silent
EXPOSE 80
RUN chown -R node /app
USER node
CMD ["npm", "start"]