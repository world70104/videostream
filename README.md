# videostream

- server
  rtmp streaming server( Node JS )
      ex: node server.js
  Simple-RTMP-Server( linux or mac )
       https://github.com/ossrs/srs
       This server is very stable
       IMPORTANT: use this server
       For rtmp server excuting
       https://github.com/ossrs/srs/wiki/v1_EN_SampleRTMP
       ex:  ./objs/srs -c conf/rtmp.conf
       IMPORTANT: In rtmp.conf file, change port ( Listen xxxx: )
       xxxx: port number
       max_connections xxx; ( default: 10000 <- change 250 below  )
       
- player
  player rtmp data
- client
  android publish rtmp to server 

manual rtmp publish tool
  * OBS
