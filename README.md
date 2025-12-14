# config files - too lazy to make a proper readme icl

all my config files contains:

kitty config

sddm greeter theme

How to install sddm theme:

1. extract the content via "tar -xvf sddm-theme.tar.gz"
2. move it to the themes directory via "sudo mv TerminalStyleLogin /usr/share/sddm/themes/"
3. configure the greeter config via "sudo nano /etc/sddm.conf" and add the following Line

[Theme]

Current=TerminalStyleLogin

4. restart sddm service via "sudo systemctl restart sddm.service"


# automation script coming soon
