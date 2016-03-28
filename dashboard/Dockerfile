FROM node:latest

RUN mkdir /dashboard
WORKDIR /dashboard
COPY config.json /dashboard/

RUN npm install -g parse-dashboard
# ENV APP_ID
# ENV MASTER_KEY
# ENV SERVER_URL
# ENV PARSE_DASHBOARD_ALLOW_INSECURE_HTTP=1

CMD parse-dashboard --config /dashboard/config.json --allowInsecureHTTP=1
#--appId $APP_ID --masterKey $MASTER_KEY --serverURL "${SERVER_URL}"
