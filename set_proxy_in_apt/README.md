Open apt.conf file
```bash
sudo nano /etc/apt/apt.conf
```
Now write the following in apt.conf file
```bash
Acquire::http::proxy "http://user:password@proxy.serever.name:port/";
Acquire::https::proxy "https://user:password@proxy.serever.name:port/";
Acquire::ftp::proxy "ftp://user:password@proxy.serever.name:port/";
Acquire::socks::proxy "socks://user:password@proxy.serever.name:port/";
```
