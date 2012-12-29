# Upcoming releases

# 0.0.1
- configure log files
- directory with files for individual configurations
- static file serve directory
- enable gzip
- Host, Routes configuration
- Routes terminate with
--- static serve
--- Proxy
--- zeromq handler
- each server
--- access log
--- error log
- deamonize each with chroot
https://github.com/nodejitsu/node-http-proxy
https://github.com/cloudhead/node-static (or) just connect-static
connect-compress
