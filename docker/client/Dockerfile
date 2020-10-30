FROM node:15-alpine

RUN apk update && \
    npm i -g @vue/cli

RUN cd / && \
    yarn add vue-template-compiler && \
    cd ./node_modules/vue-template-compiler/ && \
    sed -i -e "s/var vueVersion = .*/var vueVersion = undefined/" index.js
