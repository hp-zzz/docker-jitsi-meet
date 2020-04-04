FROM jitsi/web:latest
#
RUN ln -sfv /DEV_DIR/room.html /usr/share/jitsi-meet/room.html
RUN ln -sfv /DEV_DIR/index.html /usr/share/jitsi-meet/index.html
RUN ln -sfv /DEV_DIR/css/all.css /usr/share/jitsi-meet/css/all.css
RUN ln -sfv /DEV_DIR/css/hack.css /usr/share/jitsi-meet/css/hack.css
RUN ln -sfv /DEV_DIR/hack.js /usr/share/jitsi-meet/libs/hack.js
RUN ln -sfv /DEV_DIR/interface_config.js /usr/share/jitsi-meet/libs/interface_config.js
RUN ln -sfv /DEV_DIR/lang/main-zhCN.json /usr/share/jitsi-meet/lang/main-zhCN.json
#RUN ln -sfv /DEV_DIR/libs/app.bundle.min.js /usr/share/jitsi-meet/libs/app.bundle.min.js
#RUN ln -sfv /DEV_DIR/libs/dial_in_info_bundle.min.js /usr/share/jitsi-meet/libs/dial_in_info_bundle.min.js
RUN ln -sfv /DEV_DIR/images/logo1.png /usr/share/jitsi-meet/images/logo1.png 
RUN ln -sfv /DEV_DIR/images/logo2.png /usr/share/jitsi-meet/images/logo2.png 
RUN ln -sfv /DEV_DIR/images/logo2.png /usr/share/jitsi-meet/images/favicon.ico


EXPOSE 80 443

VOLUME ["/config", "/DEV_DIR", "/etc/letsencrypt"]
