# Hosting by python
- pkg install python
- python -m http.server 8080 &
- cloudflared tunnel --url http://localhost:8080

# apk Decompiling
* pkg install tur-repo
pkg update
* pkg install openjdk-21
[if no found then pkg search openjdk ]
* pkg install wget
wget https://raw.githubusercontent.com/AbhiModzNextYT/Termux-Java/master/install.sh
bash install.sh
* java -v
* wget https://bitbucket.org/iBotPeaches/apktool/downloads/apktool_2.10.0.jar -O apktool.jar
* chmod +x apktool apktool.jar
* mv apktool apktool.jar $PREFIX/bin/
* apktool --version
* apktool d file_ka_naam.apk

## Decompile hone ke baad kya milega?
* AndroidManifest.xml: Ye app ki sabse important file hai. Isme app ki permissions (camera, internet, etc.), package name, aur saari screens (Activities) ki detail hoti hai.
* res/ (Resources): Iske andar app ka saara visual material hota hai. Jaise:
drawable-xxxx: App ke icons aur images
layout: App ki screens kaise dikhengi (XML files).
values: App mein use hone wale saare texts (strings.xml) aur colors
* androidManifest.xml: App ki main configuration file
* smali/, smali_classes2/, etc.: Ye sabse zaruri hain. Ye app ka Source Code hai. Android apps .dex files use karti hain, Apktool unhe .smali files mein tod deta hai.
* assets/: Isme extra files hoti hain jaise fonts, database files, ya kabhi-kabhi extra plugins.

