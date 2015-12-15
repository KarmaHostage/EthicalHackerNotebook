#CryptCat

###What it is

-- TODO

###Basic Usage

Open a connection on local port 1337 and pipe all output to **outputfile**

    cryptcat -l -p 1337 -n > outputfile

Connect back to your machine on port 1337 and send a file

    cryptcat 192.168.1.202 1337 < /root/inputfile
