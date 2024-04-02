1. The library modified based on the master version of NGINX to be compatible with GMSSL encryption.
2. nginx with gmssl-v2
2. compile args:
``
./auto/configure --with-cc=cl --prefix=. --with-select_module --with-poll_module --with-file-aio --with-http_ssl_module --with-http_v2_module --with-http_realip_module --with-http_addition_module --with-http_sub_module --with-http_dav_module --with-http_flv_module --with-http_mp4_module --with-http_gunzip_module --with-http_gzip_static_module --with-http_auth_request_module --with-http_random_index_module --with-http_secure_link_module --with-http_slice_module --with-http_stub_status_module --with-mail --with-mail_ssl_module --with-mail_ssl_module --with-stream --with-stream_ssl_module --with-stream_realip_module --with-stream_ssl_preread_module --with-pcre --with-openssl=../GmSSL --with-pcre=./pcre2 --with-zlib=./zlib --add-module=./modules/nginx-sticky-module-ng-master
``
3. Compiler version used is Visual Studio 2022 Preview Or gcc13.2
