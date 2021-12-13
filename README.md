# Ref

Set project name

- mysql
    - set db name
- nest
    - nest new project-name
    - `src/main.ts` add app.setGlobalPrefix('api');
- nginx
    - https://stackoverflow.com/a/68493209/12225509
    - https://gist.github.com/ndrut/4632758
    - https://stackoverflow.com/questions/45254455/can-we-use-both-nginx-and-pm2-for-node-js-production-deployment
- next
    - https://github.com/vercel/next.js/tree/canary/examples/with-docker
        - https://github.com/nodejs/docker-node/tree/b4117f9333da4138b03a546ec926ef50a31506c3#nodealpine - why add libc6-compat
        - https://github.com/gliderlabs/docker-alpine/issues/55#issuecomment-264319037 - dns problem
    - https://github.com/steveholgado/nextjs-docker-pm2-nginx
- nginx,node,mysql,react
    - https://github.com/mosesreigns/Build-and-Dockerize-a-Full-stack-React-app-with-Node.js-MySQL-and-Nginx-for-reverse-proxy
    - https://www.digitalocean.com/community/questions/how-to-host-multiple-docker-containers-on-a-single-droplet-with-nginx-reverse-proxy
