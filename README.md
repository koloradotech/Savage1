# savage


!/bin/bash

# Install Core Packages
echo Installing Core Packages...
 apt-get install -y libbz2-dev libcppunit-dev libcurl4-openssl-dev libffi-dev libfmt-dev libgdbm-dev libglib2.0-dev libglib2.0-dev-bin libgmp-dev libgspell-1-dev libgtkmm-3.0-dev libgtksourceviewmm-3.0-dev liblog4cpp5-dev libncurses5-dev libnss3-dev liborc-0.4-dev libosmocore-dev libreadline-dev libspdlog-dev libsqlite3-dev libssl-dev libtool libuchardet-dev libxml2 libxml++2.6-dev libxml2-dev libxslt1-dev zlib1g-dev python python3-flask python3-future python3-geoip python3-httplib2 python3-numpy python3-paramiko python3-pip python3-psutil python3-pycurl python3-requests python3-scapy python3-scipy python3-setuptools python3-urllib3 python3-virtualenv python3-wheel 7zip p7zip-full p7zip-rar rar unrar wget ruby curl perl apache2 asciinema autoconf autopsy binutils binwalk build-essential cmake debootstrap default-jre dirmngr dkms doxygen easytag filezilla g++ gcc gconf2 ghex git gnuradio gnuradio-dev gr-osmosdr hexedit httrack jq kate macchanger make mtools net-tools  pidgin pkg-config  screen screenfetch secure-delete simplescreenrecorder apt-transport-https apt-utils ca-certificates ca-certificates certbot software-properties-common squashfs-tools subversion swig tree vim  xorriso libavcodec-extra-57 libavformat-dev libavresample-dev libavutil-dev libdc1394-22-dev libjpeg-turbo

# install Download Packages
echo Installing Download Packages
 apt-get install -y synaptic discover snapd flatpak

# Install Ubuntu Studio packages
echo Installing Ubuntu Studio packages
 apt-get install -y ubuntustudio-graphics ubuntustudio-video ubuntustudio-publishing ubuntustudio-photography

# Update and clean
echo Updating and cleaning
 apt purge libreooffice* -y
 apt-get update &&  apt-get upgrade -y
 apt-get autoremove &&  apt-get autoclean -y

# Add Pen Testing PPAs
echo Adding Pen Testing PPAs
 add-apt-repository ppa:aduroideja/androidsecurity
 add-apt-repository ppa:cybersec/pantobuntu-tools
 add-apt-repository ppa:cyborg-hawk/stable
 add-apt-repository ppa:j0lly/bb4test
 add-apt-repository ppa:darklordpaunik8880/darksmsaucy2
 add-apt-repository ppa:icedhell-anouss/phoenixos
 add-apt-repository ppa:3lack7ragon/blackdragon-penetration-testing3-ppa
 add-apt-repository ppa:cybersec/trusty-test

# update gpg keys for y-ppa 
echo Updating gpg keys for y-ppa
 add-apt-repository ppa:webupd8team/y-ppa-manager
 apt-get update
 apt-get install y-ppa-manager

# Update the gpg keys for launchpad
echo Updating gpg keys for launchpad
 apt-get install launchpad-getkeys
 launchpad-getkeys

# Add snaps
 snap install opensearch
 snap install pycharm-educational --classic
 snap install pycharm-professional --classic
 snap install pycharm-community --classic
 snap install intellij-idea-ultimate --classic
 snap install lxd
 snap install go --classic
 snap install webstorm --classic
 snap install beekeeper-studio
 snap install android-studio --classic
 snap install phpstorm --classic

 apt-get update &&  apt-get upgrade -y

# -------------------------------------------

## Install Blackbuntu DEB packages collection
git clone https://github.com/snowcittysolutions/2BLACKBUNTU-debpackages.git

download all .deb files from the repo and install them, seperating them by category {category= Cracking Tools Exploitation Tools Forensics tools Mobile Tools Networking Tools OSINT Tools Password Attacks Tools Sniffing & Spoofing Tools Stress Testing Tools Web Attack Tools Reverse Engineering Tools Utilities Tools Vulnerability Analysis Tools Web Applications Tools Wireless Tools} and then create a menu  
#

# Blackbuntu DEB packages collection
# Packages
[name](https://GIT/WEBSITE.com) - 
#### Cracking tools
[crowbar](https://github.com/galkan/crowbar)
[gpp-decrypt](https://blog.carnal0wnage.com/2012/10/group-policy-preferences-and-getting.html)
[rainbowcrack](https://project-rainbowcrack.com/)
[rsmangler](https://digi.ninja/projects/rsmangler.php)
[truecrack](https://github.com/lvaccaro/truecrack)
* * *
#### Exploitation tools
[cge](http://www.blackangels.it/)
[commix](https://github.com/commixproject/commix)
[exe2hex](https://github.com/acjsec/exe2bam)
[jexboss](https://github.com/joaomatosf/jexboss)
[libenom](https://github.com/Bounteous17/libenom)
[routersploit](https://github.com/threat9/routersploit)
[sharpmeter](https://github.com/vvalien/SharpMeter/)
[shellnoob](https://github.com/reyammer/shellnoob)
* * *
#### Forensics tools
[ddrescue](http://www.garloff.de/kurt/linux/ddrescue/)
[dumpzilla](https://www.dumpzilla.org/)
[pdfid](https://blog.didierstevens.com/programs/pdf-tools/)
[pdf-parser](https://blog.didierstevens.com/programs/pdf-tools/)
* * *
#### Hardening tools
[dex2jar](https://github.com/pxb1988/dex2jar)
* * *
#### Information Gathering tools
[enum4linux](https://www.portcullis-security.com/)
[fierce](https://github.com/mschwager/fierce)
[gnmap](https://github.com/themightyshiv/gnmap)
[lbd](http://ge.mine.nu/code/)
[linenum](https://github.com/rebootuser/LinEnum)
[phoneinfoga](https://github.com/sundowndev/phoneinfoga)
[smtp-user-enum](https://pentestmonkey.net/tools/user-enumeration/smtp-user-enum)
* * *
#### Networking tools
[cryptcat](https://packages.ubuntu.com/focal/cryptcat)
[cymothoa](http://cymothoa.sourceforge.net/)
[dns2tcp](https://packages.ubuntu.com/focal/dns2tcp)
[httptunnel](https://packages.ubuntu.com/focal/httptunnel)
[nishang](https://github.com/samratashok/nishang)
[powersploit](https://github.com/PowerShellMafia/PowerSploit)
[pwnat](http://samy.pl/pwnat/)
[reverser](https://github.com/Hood3dRob1n/Reverser)
[webshells](https://www.kali.org/tools/webshells/)
* * *
#### Reverse Engineering tools
[javasnoop](https://code.google.com/archive/p/javasnoop/)
[jad](http://www.javadecompilers.com/jad)
* * *
#### Sniffing & Spoofing tools
[mitmdump](https://mitmproxy.org/)
[mitmproxy](https://mitmproxy.org/)
[mitmweb](https://mitmproxy.org/)
[sniffjoke](https://github.com/vecna/sniffjoke)
[webscarab](http://dawes.za.net/rogan/webscarab/)
[zaproxy](https://www.zaproxy.org/)
* * *
#### Stress Testing tools
[iaxflood](http://www.hackingexposedvoip.com/sec_tools.html)
[rtpflood](http://www.hackingexposedvoip.com/sec_tools.html)
[thc-ssl-dos](https://www.thc.org/thc-ssl-dos/)
[udpflood](http://www.hackingexposedvoip.com/sec_tools.html)
* * *
#### Utilities tools
[dracnmap](https://github.com/screetsec/Dracnmap)
[ridenum](https://github.com/trustedsec/ridenum)
[subbrute](https://github.com/TheRook/subbrute)
[webtrace](https://neoslab.com)
* * *
#### Vulnerability Analysis tools
[bed](http://ww5.snake-basket.de/)
[jsql-injection](https://github.com/ron190/jsql-injection)
[sfuzz](http://aconole.brad-x.com/programs/sfuzz.html)
[tnscmd10g](http://www.red-database-security.com/)
[unix-privesc](https://pentestmonkey.net/tools/audit/unix-privesc-check)
* * *
#### Web Applications tools
[cmsmap](https://github.com/Dionach/CMSmap)
[dirbuster](https://www.owasp.org/index.php/Category:OWASP_DirBuster_Project)
[hurl](https://github.com/fnord0/hURL)
* * *
#### Wireless tools
[blueranger](http://www.hackfromacave.com/projects/blueranger.html)
[fluxion](https://github.com/FluxionNetwork/fluxion)
[wifi-honey](https://www.digininja.org/projects/wifi_honey.php7)
[wps-breaker](https://github.com/SilentGhostX/HT-WPS-Breaker)

Create new Catagory-NAME in MENU and Seperate by Catagory
# Cracking tools
 crowbar gpp-decrypt rainbowcrack rsmangler truecrack wifiphisher aircrack-ng burpsuite crunch hashcat john johnny hashcat hydra medusa ophcrack patator sqlmap thc-hydra wordlists  
# Exploitation tools
 cge commix crackmapexec exe2hex jexboss libenom metasploit routersploit routersploit sharpmeter shellnoob sqlmap w3af webscarab wfuzz 
# Forensics tools
binwalk bulk_extractor chntpw dc3dd ddrescue dumpzilla extundelete foremost galleta guymager hexedit mac-addr-gen mactime magicrescue pdfid pdf-parser sleuthkit volatility 
# Mobile tools
dex2jar adb shell sdk dozer dot 
# Networking tools
cryptcat cymothoa dns2tcp httptunnel nishang powersploit pwnat reverser webshells
# OSINT tools
amass sublist3r enum4linux fierce gnmap lbd linenum metagoofil phoneinfoga shodan   smtp-user-enum  theharvester whois
# Password Attacks tools
aircrack-ng burpsuite crunch hashcat john johnny hashcat hydra medusa ophcrack patator sqlmap thc-hydra wordlists
# Reverse Engineering tools
javasnoop jad 
# Sniffing & Spoofing tools
dsniff driftnet ettercap-graphical maltego mitmproxy netsniff-ng netsniff-ng-ssl netsniff-ng-ssl-sslstrip sslstrip wireshark mitmdump mitmproxy mitmweb sniffjoke sniffles webscarab zaproxy
# Stress Testing tools
iaxflood rtpflood thc-ssl-dos udpflood slowhttptest
# Utilities tools
dracnmap ridenum subbrute webtrace
# Vulnerability Analysis tools
bed jsql-injection sfuzz tnscmd10g unix-privesc
# Web Applications tools
cmsmap dirbuster hurl
# Wireless tools
blueranger fluxion wifi-honey wps-breaker fluxion

# ------------------------------------------
------------------------------------------------------
# Donload git-get.deb and install
https://github.com/grdl/git-get/releases/download/v0.5.0/git-get_0.5.0_linux_arm64.deb
     dpkg -i git-get_0.5.0_linux_arm64.deb
     apt-get install -f

### Starting Github Clone
echo Cloning Github

# Function to install .deb packages using gdebi
install_deb() {
    local deb_file="$1"
    if ! dpkg -s "${deb_file%.deb}" &>/dev/null; then
        sudo gdebi -n "$deb_file" || {
            echo "Failed to install $deb_file" >> error_log.txt
            echo "Reason: Error during install" >> error_log.txt
        }
    else
        echo "$deb_file is already installed."
    fi
}

# Function to process directories
process_directory() {
    local dir="$1"
    local readme_file
    local script_found=false

    # Check for README.md
    if [[ -f "$dir/README.md" ]]; then
        readme_file="$dir/README.md"
        echo "Processing $readme_file"
        # Here you can add logic to read and process the README.md
    else
        echo "No README.md found in $dir."
    fi

    # Check for .deb files
    find "$dir" -maxdepth 4 -name "*.deb" -exec bash -c 'install_deb "$0"' {} \;

    # Look for executable scripts
    for script in "$dir"/*; do
        if [[ -x "$script" ]]; then
            if [[ "$script" == *Config* || "$script" == *build* || "$script" == *make* || 
                  "$script" == *install* || "$script" == *aptinstall* ]]; then
                script_found=true
                echo "Executing script: $script"
                bash "$script" || {
                    echo "Failed to execute $script" >> error_log.txt
                    echo "Reason: Unable to follow script" >> error_log.txt
                }
            fi
        fi
    done

    if ! $script_found; then
        echo "No executable scripts found in $dir."
        echo "Reason: No .sh file" >> error_log.txt
    fi
}

# Main script execution
declare -a repos=(
 "git clonehttps://github.com/insightglacier/ Dictionary-Of-Pentesting.git"
 "git clone https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE.git"
 "git clonehttps://github.com/hmaverickadams/Beginner-Network-Pentesting.git"   
 "git clone https://github.com/Micle5858/PENTESTING-BIBLE.git"
 "git clonehttps://github.com/Rayyan-appsec/ALL-PENTESTING-BIBLE.git"
 git clone https://github.com/insightglacier/Dictionary-Of-Pentesting.git"
 "git clone https://github.com/blaCCkHatHacEEkr/PENTESTING-BIBLE.git"
 "git clone https://github.com/hmaverickadams/Beginner-Network-Pentesting.git"
 "git clone https://github.com/Micle5858/PENTESTING-BIBLE.git"
 "git clone https://github.com/Rayyan-appsec/ALL-PENTESTING-BIBLE.git"
 "git clone https://github.com/CyberAlbSecOP/Awesome_CyberSec_Bible.git"
 "git clone https://github.com/readloud/Pentesting-Bible.git"
 "git clone https://github.com/UkraineSecOps/PenTestingTutorials.git"
 "git clone https://github.com/PacktPublishing/Ethical-Hacking-and-CompTIA-PenTest-Exam-Prep-PT0-002-.git"
 "git clone https://github.com/luigigubello/PayloadsAllThePDFs.git"
 "git clone https://github.com/rajkumardusad/IP-Tracer.git"
 "git clone https://github.com/palahsu/DDoS-Ripper.git"
 "git clone https://github.com/kurogai/100-redteam-projects.git"
 "git clone https://github.com/EONRaider/blackhat-python3.git"
 "git clone https://github.com/TryCatchHCF/Cloakify.git"
 "git clone https://github.com/jaykali/hackerpro.git"
 "git clone https://github.com/arch3rPro/PentestTools.git"
 "git clone https://github.com/Hack-with-Github/Awesome-Hacking.git"
 "git clone https://github.com/trustedsec/social-engineer-toolkit.git"
 "git clone https://github.com/cyver-core/ultimate-pentest-tools-list.git"

 # Mobile##

 # Mobile-Security-Framework-MobSF
 "git clone https://github.com/Mobile-Security-Framework-MobSF.git"
 # all-in-one mobile application (Android/iOS/Windows)

 "git clone https://github.com/androguard/androguard.git"
 "git clone https://github.com/vaib25vicky/awesome-mobile-security.git"
 "git clone https://github.com/Hrishikesh7665/Android-Pentesting-Checklist.git"
 "git clone https://github.com/AzeemIdrisi/PhoneSploit-Pro.git"
 
 ### Platforms ##

 # 1N3 Sn1per
 "git clone https://github.com/1N3/Sn1per.git"
 # Attack Surface Management Platform 

 ### scripts###
 "git clone https://github.com/killswitch-GUI/PenTesting-Scripts.git"
 "git clone https://github.com/hak5/bashbunny-payloads.git"
 "git clone https://github.com/hak5/packetsquirrel-payloads.git"
 "git clone https://github.com/liamg/gitjacker.git"
 "git clone https://github.com/harsh-bothra/learn365.git"
 "git clone https://github.com/hak5/usbrubberducky-payloads.git"

 ### Wireless ###

 "git clone https://github.com/Tylous/SniffAir.git"
 "git clone https://github.com/casterbyte/NetworkNightmare.git"
 "git clone https://github.com/sundowndev/hacker-roadmap.git"


 ### Osint ###  

 "git clone https://github.com/jivoi/awesome-osint.git"
 "git clone https://github.com/wddadk/Offensive-OSINT-Tools.git"
 "git clone https://github.com/TheBurnsy/Vehicle-OSINT-Collection.git"
 "git clone https://github.com/UndeadSec/SocialFish.git"
 "git clone https://github.com/lockfale/OSINT-Framework.git"
 "git clone https://github.com/sinwindie/OSINT.git"
 "git clone https://github.com/twelvesec/gasmask.git"
 "git clone https://github.com/jasperan/whatsapp-osint.git"
 "git clone https://github.com/Lucksi/Mr.Holmes.git"
 "git clone https://github.com/wssheldon/osintui.git"
 "git clone https://github.com/CScorza/OSINT-FORENSICS-MOBILE.git"
 "git clone https://github.com/wddadk/Offensive-OSINT-Tools.git"
 "git clone https://github.com/dev-lu/osint_toolkit.git"
 "git clone https://github.com/Nhoya/gOSINT.git"
 "git clone https://github.com/apurvsinghgautam/dark-web-osint-tools.git"
 "git clone https://github.com/s0md3v/Pho"
 "git clone https://github.com/laramies/theHarvester.gitton.git"
 "git clone https://github.com/cipher387/osint_stuff_tool_collection.git"
 "git clone https://github.com/DedSecInside/TorBot.git"
 "git clone https://github.com/Ph055a/OSINT_Collection.git"
 "git clone https://github.com/milo2012/osintstalker.git"
 "git clone https://github.com/Jieyab89/OSINT-Cheat-sheet.git"
 "git clone https://github.com/SharadKumar97/OSINT-SPY.git"
 "git clone https://github.com/smicallef/spiderfoot.git"
 "git clone https://github.com/Lissy93/web-check.git"
 "git clone https://github.com/cipher387/API-s-for-OSINT.git"
 "git clone https://github.com/nahamsec/lazyrecon.git"

 #Google Dorks

 #BullsEye0 google_dork_list
 "git clone https://github.com/BullsEye0/google_dork_list.git"
 #13.760 Dorks. find Vulnerable Websites that Indexed in Google Search 
 ##Result Author: Jolanda de Koff 
	
 # Proviesec google-dorks
 "git clone https://github.com/Proviesec/google-dorks.git"
 ##Useful Google Dorks for WebSecurity and Bug Bounty 

 #IvanGlinkin Fast-Google-Dorks-Scan
 "git clone https://github.com/IvanGlinkin/Fast-Google-Dorks-Scan.git"
 #collect all the possible Google dorks search combinations 
 ##and to find the information

 #TakSec google-dorks-bug-bounty 
 "git clone https://github.com/TakSec/google-dorks-bug-bounty.git"
 #bA list of Google Dorks for Bug Bounty, Web Application 
 ##Security, and Pentesting 
-
 #opsdisk pagodo 
 "git clone https://github.com/opsdisk/pagodo.git"
 #pagodo (Passive Google Dork) - Automate Google Hacking
 ##Database scraping and searching 

 #USSCltd dorks
 "git clone https://github.com/USSCltd/dorks.git"
 #google hack database automation tool 
	
 # Tobee1406 Awesome-Google-Dorks
 "git clone https://github.com/Tobee1406/Awesome-Google-Dorks.git"
 # A collection of Awesome Google Dorks. 

 # Misc
 "git clone https://github.com/thehackingsage/hacktronian.git"
 "git clone https://github.com/m14r41/PentestingEverything.git"
 "git clone https://github.com/m4n3dw0lf/pythem.git"
 "git clone https://github.com/gokulapap/Reconator.git"
 "git clone https://github.com/swisskyrepo/HardwareAllTheThings.git"
 "git clone https://github.com/Chudry/Xerror.git"
 "git clone https://github.com/jmortega/python-pentesting.git"
 "git clone https://github.com/Ha3MrX/Hacking.git"
 "git clone https://github.com/redcode-labs/Citadel.git"
 "git clone https://github.com/stampery/mongoaudit.git"
 "git clone https://github.com/pop3ret/AWSome-Pentesting.git"
 "git clone https://github.com/DonatoReis/Secbuild.git"
 "git clone https://github.com/takuzoo3868/penta.git"
 "git clone https://github.com/danieldurnea/FBI-tools.git"
 "git clone https://github.com/RhinoSecurityLabs/Swagger-EZ.git"
 "git clone https://github.com/p1ngul1n0/blackbird.git"
 "git clone https://github.com/gat3way/AirPirate.git"
 "git clone https://github.com/hmaverickadams/Beginner-Network-Pentesting.git"
 "git clone https://github.com/0x90/vpn-arsenal.git"
 "git clone https://github.com/v3n0m-Scanner/V3n0M-Scanner.git"
 "git clone https://github.com/Ranginang67/Firecrack.git"
 "git clone https://github.com/arch3rPro/PentestTools.git"
 "git clone https://github.com/Telefonica/HomePWN.git"
 "git clone https://github.com/infosecn1nja/Red-Teaming-Toolkit.git"
 "git clone https://github.com/InfosecMatter/Minimalistic-offensive-security-tools.git"
 "git clone https://github.com/mapluisch/ChatGPT-without-login.git"
 "git clone https://github.com/VenezuelanHackingTeam/blackbuntu.git"
 "git clone https://github.com/CyberSecurityUP/PenTest-Consulting-Creator.git"
 "git clone https://github.com/devploit/pwny.cc.git"
 "git clone https://github.com/OWASP/Nettacker.git"
 "git clone https://github.com/ZephrFish/Blog_Backup.git"
 "git clone https://github.com/M4cs/DarkSpiritz.git"
 "git clone https://github.com/PacktPublishing/Ethical-Hacking-and-CompTIA-PenTest-Exam-Prep-PT0-002-.git"
 "git clone https://github.com/rng70/Hacking-Resources.git"
 "git clone https://github.com/CyberSecArmy/AWS-Offensive-Exploitation---Pentesting.git"
 "git clone https://github.com/sarthak1598/PentestingWithPython-ToolBox.git"
 "git clone https://github.com/simplerhacking/Evilginx3-Phishlets.git"
 "git clone https://github.com/Sh0ckFR/Infosec-Useful-Stuff.git"
 "git clone https://github.com/FreeZeroDays/OSS.git"
 "git clone https://github.com/t3l3machus/PowerShell-Obfuscation-Bible.git"
 "git clone https://github.com/arch3rPro/PentestTools.git"
 "git clone https://github.com/mgeeky/Penetration-Testing-Tools.git"
 "git clone https://github.com/Chudry/Xerror.git"
 "git clone https://github.com/urbanadventurerWhatWeb.git"
 "git clone https://github.com/ANK1036Official/Git_Pentesting_Toolkit.git"
 "git clone https://github.com/pablosnt/rekono.git"
 "git clone https://github.com/M4cs/BabySploit.git"
 "git clone https://github.com/cracker911181/Cracker-Tool.git"
 "git clone https://github.com/sqlmapproject/sqlmap.git"
 "git clone https://github.com/dmayer/idb.git"
 "git clone https://github.com/screetsec/my.git"
 "git clone https://github.com/AlexisAhmed/Python3PentestingTools.git"
 "git clone https://github.com/pikpikcu/Pentest-Tools-Framework.git"
 "git clone https://github.com/may215/awesome-termux-hacking.git"
 "git clone https://github.com/pikpikcu/Pentest-Tools-Framework.git"
 "git clone https://github.com/f/awesome-chatgpt-prompts.git"
 "git clone https://github.com/pawelborkar/awesome-repos.git"
 "git clone https://github.com/AlphaCorpIN/Hacking-Repos.git"
 "git clone https://github.com/PacktPublishing/Ethical-Hacking-A-Hands-On-Approach-to-Ethical-Hacking.git"
 "git clone https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet.git"
)

# Clone repositories and process them
for repo in "${repos[@]}"; do
    echo "Cloning repository: $repo"
    git clone "$repo"
    repo_name=$(basename "$repo" .git)
    process_directory "$repo_name"
done

echo "Processing completed."



