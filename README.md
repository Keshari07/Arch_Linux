# Arch_Linux
The image can be burned to a DVD, mounted as an ISO file, or be directly written to a USB flash drive. It is intended for new installations only; an existing Arch Arch Linux Downloads
Release Info
The image can be burned to a DVD, mounted as an ISO file, or be directly written to a USB flash drive. It is intended for new installations only; an existing Arch Linux system can always be updated with pacman -Syu.

Current Release: 2024.04.01
Included Kernel: 6.8.2
ISO Size: 955.3 MB
Installation Guide
Resources:
Issue tracker
Mailing List
Existing Arch Users
If you are an existing Arch user, there is no need to download a new ISO to update your existing system. You may be looking for an updated mirrorlist instead.

BitTorrent Download (recommended)
If you can spare the bytes, please leave the client open after your download is finished, so you can seed it back to others.
A DHT capable client is required. A WebSeed capable client is recommended for fastest download speeds.

Magnet link for 2024.04.01 
Torrent for 2024.04.01
Netboot
If you have a wired connection, you can boot the latest release directly over the network.

Arch Linux Netboot
Vagrant images
Vagrant images for libvirt and virtualbox are available on the Vagrant Cloud. You can bootstrap the image with the following commands:

vagrant init archlinux/archlinux
vagrant up
Docker image
The official Docker image is available on Docker Hub. You can run the image with the following command:

docker run -it archlinux
VM images
Official virtual machine images are available for download on our GitLab instance, more information is available in the README.

HTTP Direct Downloads
In addition to the BitTorrent links above, install images can also be downloaded via HTTP from the mirror sites listed below. Please ensure the download image matches the checksum from the sha256sums.txt or b2sums.txt file linked below.

Checksums and signatures
File integrity checksums and PGP signatures for the latest releases can be found below:

ISO
PGP signature
PGP fingerprint: 0x54449A5C
SHA256: 52aea58f88c9a80afe64f0536da868251ef4878de5a5e0227fcada9f132bd7ab
BLAKE2b: 30ccdbcbd00c222842332935358d6be7f64d19c21bb992b20a0ef6fb1d7b80c73508952593fd907c04dc3f3fb4552520047daa5681cd94d00860e557c4be72e2
Bootstrap tarball
PGP signature
sha256sums.txt
b2sums.txt
Download verification
Verify the BLAKE2b checksums as follows:

$ b2sum -c b2sums.txt
To verify the PGP signature using Sequoia, first download the release signing key from WKD:
$ sq network wkd fetch pierre@archlinux.org -o release-key.pgp
With this signing key, verify the signature:
$ sq verify --signer-file release-key.pgp --detached archlinux-2024.04.01-x86_64.iso.sig archlinux-2024.04.01-x86_64.iso
Alternatively, using GnuPG, download the signing key from WKD:

$ gpg --auto-key-locate clear,wkd -v --locate-external-key pierre@archlinux.org
Verify the signature:
$ gpg --keyserver-options auto-key-retrieve --verify archlinux-2024.04.01-x86_64.iso.sig archlinux-2024.04.01-x86_64.iso
Worldwide
geo.mirror.pkgbuild.com
rackspace.com
 Australia
aarnet.edu.au
cicku.me
digitalpacific.com.au
fcix.net
geo.mirror.pkgbuild.com
rackspace.com
 Austria
alwyzon.net
kescher.at
reisenbauer.ee
zachlge.org
 Azerbaijan
hostart.az
 Brazil
ufscar.br
 Bulgaria
darklinux.uk
telepoint.bg
uni-plovdiv.net
 Canada
0xem.ma
arch.mirror.winslow.cloud
cicku.me
cpsc.ucalgary.ca
csclub.uwaterloo.ca
evolution-host.com
mirror.quantum5.ca
muug.ca
powerfly.ca
ptse.host
scd31.com
xenyth.net
 Chile
anquan.cl
elmirror.cl
hnd.cl
ufro.cl
 China
aliyun.com
bfsu.edu.cn
cqu.edu.cn
hit.edu.cn
jlu.edu.cn
jxust.edu.cn
neusoft.edu.cn
nju.edu.cn
njupt.edu.cn
nyist.edu.cn
qlu.edu.cn
qvq.net.cn
redrock.team
shanghaitech.edu.cn
sjtug.sjtu.edu.cn
tuna.tsinghua.edu.cn
ustc.edu.cn
wsyu.edu.cn
xjtu.edu.cn
 Colombia
atlas.net.co
fcix.net
 Czechia
dkm.cz
geo.mirror.pkgbuild.com
gluttony.sin.cvut.cz
it4i.cz
nic.cz
sh.cvut.cz
 Denmark
dotsrc.org
one.com
safe-con.dk
 Estonia
cspacehostings.com
repo.br.ee
xtom.ee
 Finland
arch.mcstrugs.org
arctic.lol
kyberorg.fi
mirror.5i.fi
sl-chat.ru
srv.fail
wuki.li
yhtez.xyz
 France
cyberbits.eu
eric.ovh
gandi.net
hogwarts.fr
ibakerserver.pt
its-tps.fr
jordanrey.me
jtremesay.org
juline.tech
labhouse.fr
mailtunnel.eu
mirrors.celianvdb.fr
nimukaito.net
oldsql.cc
ovh.net
spaceint.fr
sysa.tech
thekinrar.fr
theo546.fr
wormhole.eu
wptheme.fr
yourlabs.org
 Georgia
grena.ge
 Germany
agdsn.de
cicku.me
clientvps.com
cmt.de
codefionn.eu
dogado.de
f4st.host
fau.de
fef.moe
fem.tu-ilmenau.de
gnomus.de
homeinfo.de
hugo-betrugo.de
informatik.tu-freiberg.de
iusearchbtw.nl
janbruckner.de
jensgutermuth.de
kescher.at
kumi.systems
kurdy.org
leaseweb.net
metalgamer.eu
mikrogravitation.org
mirror.lcarilla.de
moson.org
n-ix.net
nekos.host
netcologne.de
niyawe.de
orbit-os.com
oth-regensburg.de
phinau.de
pseudoform.org
richard-neumann.de
rwth-aachen.de
satis-faction.de
selfnet.de
spline.inf.fu-berlin.de
sunred.org
thaller.ws
ubrco.de
unixpeople.org
wrz.de
wtnet.de
xtom.de
 Greece
greeklug.gr
 Hong Kong
geo.mirror.pkgbuild.com
koddos.net
rackspace.com
wtako.net
xtom.com.hk
 Hungary
ek-cer.hu
quantum-mirror.hu
quantum-mirror.hu
quantum-mirror.hu
 Iceland
flokinet.net
opensource.is
system.is
 India
4v1.in
abhy.me
albony.in
albony.in
albony.in
cicku.me
garudalinux.org
mirror.net.in
nxtgen.com
piconets.webwerks.in
sahil.world
 Indonesia
citrahost.com
gi.co.id
jagoanhosting.com
mirror.ditatompel.com
papua.go.id
repository.id
telkomuniversity.ac.id
uny.ac.id
 Iran
bardia.tech
 Israel
interhost.co.il
isoc.org.il
mivzakim.net
 Italy
archmirror.it
 Japan
cat.net
cicku.me
jaist.ac.jp
jing.rocks
nishi.network
saebasol.org
 Kazakhstan
hoster.kz
ps.kz
 Kenya
liquidtelecom.com
 Latvia
koyanet.lv
 Lithuania
atviras.lt
ims.nksc.lt
 Luxembourg
archmirror.xyz
 Mauritius
archlinux-mirror.cloud.mu
 Mexico
jsc.mx
 Moldova
hacktegic.com
ihost.md
mangohost.net
 Monaco
qontinuum.space
 Netherlands
bouwhuis.network
cj2.nl
daan.vodka
erickochen.nl
flokinet.net
i3d.net
koddos.net
lavatech.top
leaseweb.net
liteserver.nl
lyrahosting.com
neostrada.nl
pcextreme.nl
serverion.com
tarellia.net
viflcraft.top
wearetriple.com
webruimtehosting.nl
xtom.nl
 New Caledonia
nautile.nc
 New Zealand
2degrees.nz
fsmg.org.nz
ourhome.kiwi
smith.geek.nz
 North Macedonia
t-home.mk
 Norway
archlinux.no
lysakermoen.com
neuf.no
 Poland
eloteam.tk
icm.edu.pl
juniorjpdj.pl
midov.pl
psnc.pl
sakamoto.pl
skni.umcs.pl
 Portugal
barata.pt
glua.ua.pt
leitecastro.com
mirrors.up.pt
rnl.tecnico.ulisboa.pt
 Romania
chroot.ro
efect.ro
flokinet.net
hosterion.ro
nxthost.com
pidginhost.com
 Russia
kamtv.ru
kpfu.ru
lebedinets.ru
nw-sys.ru
repository.su
rol.ru
sl-chat.ru
sl-chat.ru
truenetwork.ru
yandex.ru
 Serbia
sox.rs
 Singapore
0x.sg
aktkn.sg
cicku.me
download.nus.edu.sg
guillaumea.fr
jingk.ai
sg.gs
 Slovakia
lnx.sk
 Slovenia
archimonde.ts.si
tux.si
 South Africa
allworldit.com
urbanwave.co.za
 South Korea
cicku.me
funami.tech
geo.mirror.pkgbuild.com
harukasan.org
lanet.kr
morgan.kr
siwoo.org
yuki.net.uk
 Spain
cloroformo.org
librelabucm.org
mirrors.marquitos.space
panibrez.com
 Sweden
acc.umu.se
ludd.ltu.se
lysator.liu.se
mirror.bahnhof.net
myrveln.se
osbeck.com
 Switzerland
adfinis.com
metanet.ch
mirror.puzzle.ch
theswissbay.ch
worldhotspot.org
 Taiwan
archlinux.tw
free.nchc.org.tw
ncuesaweb.ncue.edu.tw
nycu.edu.tw
yzu.edu.tw
 Thailand
cyberbits.asia
kku.ac.th
 Türkiye
linux.web.tr
 Ukraine
astra.in.ua
endpoint.ml
fastmirror.pp.ua
ip-connect.vn.ua
mirohost.net
nix.org.ua
 United Kingdom
allworldit.com
bytemark.co.uk
geo.mirror.pkgbuild.com
gethosted.online
melbourne.co.uk
mirror.infernocomms.net
mirrorservice.org
netweaver.uk
rackspace.com
slithery.uk
ukfast.co.uk
ukservers.com
vinehost.net
 United States
adectra.com
arizona.edu
arlm.tyzoid.com
ava.dev
bjg.at
bloomu.edu
cicku.me
clarkson.edu
constant.com
cybersecurity.nmt.edu
elightcap.com
ette.biz
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
fcix.net
geo.mirror.pkgbuild.com
goober.cloud
hodgepodge.dev
hostup.org
hu.fo
ialab.dsu.edu
iu13.org
k0.ae
kernel.org
leaseweb.net
leaseweb.net
leaseweb.net
leaseweb.net
lty.me
lug.mtu.edu
m.lqy.me
macarne.com
mirror.kaminski.io
misaka.one
mit.edu
ocf.berkeley.edu
octyl.net
osuosl.org
pilotfiber.com
rackspace.com
rackspace.com
rackspace.com
radwebhosting.com
rcac.purdue.edu
rit.edu
rutgers.edu
spryservers.net
square-r00t.net
stjschools.org
sudhip.com
teraswitch.com
the-repo.org
theash.xyz
tmmworkshop.com
umd.edu
vectair.net
xtom.com
zackmyers.io
zxcvfdsa.com
 Vietnam
nguyenhoang.cloud
If you want to become an Official Arch Linux Mirror please follow the instructions listed here.
