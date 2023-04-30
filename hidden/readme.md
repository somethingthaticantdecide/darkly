wget -e robots=off -r -nH --no-parent 'http://192.168.10.129/.hidden/' --reject="index.html*"
find . -type f -exec cat {} \;