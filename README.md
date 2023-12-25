# poc-proxycommand
CYBERSEC 2024

<pre>
  git clone https://github.com/DioLin/poc-proxycommand --recurse-submodules
</pre>

# edit ~/.ssh/config

<pre>
  host *.chtpt.com
  ProxyCommand /usr/bin/nc -X connect -x 192.168.0.123:8087 %h %p
</pre>
