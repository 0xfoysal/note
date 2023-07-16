https://iamsolos.gitbook.io/security_all_note/

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
