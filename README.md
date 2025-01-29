https://iamsolos.gitbook.io/security_all_note/

dvwa installation in kali 
```
https://techdhee.org/how-to-install-dvwa-in-kali-linux/
```
beef install
```
1. Run using command : beef-xss
2. give the password : like admin
3. wait some minitue
4. Either check your framwork is running : http://127.0.0.1/ui/panel
```
metasploit install
```
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
```
if you face pattern.rb problem just go 
``` 
https://hornenielsen.wordpress.com/2016/07/13/gem-install-rex-text-saves-the-day/
 ```
 ```
if command -v tmux &> /dev/null && [ -n "$PS1" ] && [[ ! "$TERM" =~ screen ]] && [[ ! "$TERM" =~ tmux ]] && [ -z "$TMUX" ]; then
  exec tmux
fi
```
ida download for linux
```
1. chmod +x idafree76_linux.run
2. ls -l
3. sudo ./idafree76_linux.run
symbolic
4. sudo ln -s /opt/idafree76_linux.run/ida64 /usr/bin
5. ida64
```
Ghidra download
```
http://www.ylmzcmlttn.com/2019/03/26/ghidra-installation-on-ubuntu-18-04-16-04-14-04/
```

Feroxbuster install
```
curl -sL https://raw.githubusercontent.com/epi052/feroxbuster/master/install-nix.sh | bash
sudo mv feroxbuster /usr/local/bin
copy config file and then create ferox-config.toml and save this location /usr/local/bin
sitting direcory for wordlist
check run :
feroxbuster -u http://bugcrowd.com/ and hit enter.
```

FFUF install
```
sudo add-apt-repository -y ppa:longsleep/golang-backports
sudo apt update        
sudo apt install -y golang-go
cd ~
go get github.com/ffuf/ffuf
sudo ln -s ~/go/bin/ffuf /usr/sbin/ffuf
```

sqlite3 tool explore db
```
ls -l 
file example.db 
sqlite3 example.db           
	.tables
	customers
	PRAGMA table_info(customers);
	SELECT * FROM customers;
```
Build in Framwork
```
https://github.com/FraternityITGroup/InfoSploit
https://github.com/milo2012/metasploitHelper 
```
some tools
```
firefox decryp
ss2johnpy
aquatone-discover   CorsMe         httprobe         pw-inspector          stackprof-flamegraph.pl
aquatone-gather     dnsprobe       httpx            qsreplace             stackprof-gprof2dot.py
aquatone-scan       dpl4hydra.sh   hydra            racc                  subfinder
aquatone-takeover   enum4linux.pl  hydra-wizard.sh  rake                  subzy
assetfinder         extract.rb     js-beautify      rspec                 threader3000
bashtop             ffuf           kxss             rubocop               tldextract
bundle              gf             ldiff            ruby-memory-profiler  waybackurls
bundler             hakrawler      naabu            ruby-parse            XSpear
BurpSuiteCommunity  htmldiff       netaddr          ruby-rewrite
cors                htmlmin        nokogiri         searchsploit
corscanner          httparty       nuclei           stackprof 
```

Direct apt install tools
```
sudo apt install iodine
sudo apt install -y tshark
sudo apt-get install -y masscan
sudo apt-get install -y commix
sudo snap install termshark
```

Automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes tool
```
python3 -m pip install ciphey --upgrade
```
cd /opt
brave.com  BurpSuiteCommunity  exploitdb  idafree-7.0  linPEAS  SecLists

vnc
```
https://mitchtech.net/vnc-setup-on-raspberry-pi-from-ubuntu/

SERVER:
sudo apt install tightvncserver
vncserver :1 -geometry 1366x768 -depth 16 -pixelformat rgb565

you should get the output as -> New ‘X’ desktop is raspberrypi:1, if it started successfully
to kill vncserver: vncserver -kill :1

CLIENT:
sudo apt install xtightvncviewer
vncviewer <ip>:5901  (or)  5900

```
