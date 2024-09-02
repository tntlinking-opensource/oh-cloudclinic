FROM nginx

ADD default.conf /etc/nginx/conf.d

COPY --from=build /app/dist /usr/share/nginx/dist
