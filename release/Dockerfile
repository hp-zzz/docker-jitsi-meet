FROM jitsi/web:latest
                   
ADD ./jitsi-meet/css/all.css                       /usr/share/jitsi-meet/css/all.css
ADD ./jitsi-meet/css/hack.css                       /usr/share/jitsi-meet/css/hack.css
ADD ./jitsi-meet/images/logo1.png                   /usr/share/jitsi-meet/images/logo1.png
ADD ./jitsi-meet/images/logo2.png                   /usr/share/jitsi-meet/images/logo2.png
ADD ./jitsi-meet/index.html                         /usr/share/jitsi-meet/index.html
ADD ./jitsi-meet/interface_config.js                /usr/share/jitsi-meet/interface_config.js
ADD ./jitsi-meet/libs/app.bundle.min.js             /usr/share/jitsi-meet/libs/app.bundle.min.js
ADD ./jitsi-meet/libs/app.bundle.min.map            /usr/share/jitsi-meet/libs/app.bundle.min.map
ADD ./jitsi-meet/libs/do_external_connect.min.js    /usr/share/jitsi-meet/libs/do_external_connect.min.js
ADD ./jitsi-meet/libs/do_external_connect.min.map   /usr/share/jitsi-meet/libs/do_external_connect.min.map
ADD ./jitsi-meet/room.html                          /usr/share/jitsi-meet/room.html
ADD ./jitsi-meet/images/logo2.png                   /usr/share/jitsi-meet/images/favicon.ico 

ADD ./jitsi-meet/lang/main-zhCN.json		    /usr/share/jitsi-meet/lang/main-zhCN.json
ADD ./jitsi-meet/lang/main.json			    /usr/share/jitsi-meet/lang/main.json

EXPOSE 80 443

VOLUME ["/config", "/DEV_DIR", "/etc/letsencrypt"]
