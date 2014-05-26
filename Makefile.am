install-exec-am:
	cp backup /usr/local/bin/backup
	chmod +x /usr/local/bin/backup
	cp backup.conf /usr/local/etc/backup.conf

install-data-am:
	[ -d /usr/local/share/doc ] || mkdir /usr/local/share/doc
	[ -d /usr/local/share/doc/backup ] || mkdir /usr/local/share/doc/backup
	cp doc/readme.html /usr/local/share/doc/backup/readme.html
	cp doc/readme.css /usr/local/share/doc/backup/readme.css

uninstall:
	[ -f /usr/local/bin/backup ] && rm -rf /usr/local/bin/backup
	[ -f /usr/local/etc/backup.conf ] && rm -rf /usr/local/etc/backup.conf
	[ -d /usr/local/share/doc/backup ] && rm -rf /usr/local/share/doc/backup
