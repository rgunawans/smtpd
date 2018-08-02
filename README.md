# smtpd

Instalasi 

  go get -v github.com/rgunawans/smtpd

Build server"

  go build main.go

Running server

  ./main
  
  
edit file smtpd.conf yang ada di dalam folder etc, sesuaikan dengan kebutuhan server

Enhancement
=========================================================
* Menambahkan ip server yang mengirimkan command yang salah ke dalam list spam
* Menambahkan command HELP untuk memberikan informasi cara mengirim email secara manual (untuk testing smtpd server)

Credits
=========================================================
* https://github.com/gleez/smtpd
* https://github.com/flashmob/go-guerrilla
* https://github.com/jhillyerd/inbucket
* https://github.com/ian-kent/Go-MailHog
* https://github.com/briankassouf/incus
* https://github.com/microcosm-cc/bluemonday
* http://gorillatoolkit.org
