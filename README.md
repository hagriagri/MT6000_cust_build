GL.iNET - MT 6000 custom build with LuCi.

What is present?
- WED enabled
- LuCi installed
- ksmbd server with automount
- openvpn-openssl
- adblock
- wireguard
- PBR
- irqbalance activated
- latest testing kernel 6.6.x

Compiled to optimize speed

How To Install?
From web interface of GL.iNET or actual openwrt flash sysupgrade.

In any case you need a package, just ask.

Package list of already installed packages.

```
adblock
avahi-dbus-daemon
base-files
blkid
busybox
ca-bundle
cgi-io
chat
collectd
collectd-mod-cpu
collectd-mod-interface
collectd-mod-iwinfo
collectd-mod-load
collectd-mod-memory
collectd-mod-network
collectd-mod-rrdtool
collectd-mod-sensors
comgt
coreutils
coreutils-sort
coreutils-stat
curl
dbus
dnsmasq-full
dropbear
e2fsprogs
eip197-mini-firmware
f2fs-tools
f2fsck
firewall4
fitblk
fstools
fwtool
getrandom
hostapd-common
ip-full
ip6tables-nft
iperf3
iptables-mod-ipopt
iptables-nft
irqbalance
iw
iwinfo
jansson4
jshn
jsonfilter
kernel
kmod-asn1-decoder
kmod-cfg80211
kmod-crypto-aead
kmod-crypto-authenc
kmod-crypto-ccm
kmod-crypto-cmac
kmod-crypto-crc32
kmod-crypto-crc32c
kmod-crypto-ctr
kmod-crypto-des
kmod-crypto-ecb
kmod-crypto-gcm
kmod-crypto-geniv
kmod-crypto-gf128
kmod-crypto-ghash
kmod-crypto-hash
kmod-crypto-hmac
kmod-crypto-hw-safexcel
kmod-crypto-lib-chacha20
kmod-crypto-lib-chacha20poly1305
kmod-crypto-lib-curve25519
kmod-crypto-lib-poly1305
kmod-crypto-manager
kmod-crypto-md4
kmod-crypto-md5
kmod-crypto-null
kmod-crypto-rng
kmod-crypto-seqiv
kmod-crypto-sha1
kmod-crypto-sha256
kmod-crypto-sha3
kmod-crypto-sha512
kmod-cryptodev
kmod-fs-exfat
kmod-fs-ext4
kmod-fs-f2fs
kmod-fs-ksmbd
kmod-fs-netfs
kmod-fs-ntfs3
kmod-fs-smbfs-common
kmod-fs-vfat
kmod-gpio-button-hotplug
kmod-hwmon-core
kmod-ifb
kmod-ip6tables
kmod-ipt-core
kmod-ipt-ipopt
kmod-leds-gpio
kmod-lib-crc-ccitt
kmod-lib-crc16
kmod-lib-crc32c
kmod-mac80211
kmod-mt76-connac
kmod-mt76-core
kmod-mt7915e
kmod-mt7986-firmware
kmod-nf-conntrack
kmod-nf-conntrack-netlink
kmod-nf-conntrack6
kmod-nf-flow
kmod-nf-ipt
kmod-nf-ipt6
kmod-nf-log
kmod-nf-log6
kmod-nf-nat
kmod-nf-reject
kmod-nf-reject6
kmod-nfnetlink
kmod-nft-compat
kmod-nft-core
kmod-nft-fib
kmod-nft-nat
kmod-nft-offload
kmod-nls-base
kmod-nls-cp437
kmod-nls-iso8859-1
kmod-nls-ucs2-utils
kmod-nls-utf8
kmod-oid-registry
kmod-ppp
kmod-pppoe
kmod-pppox
kmod-rtl8192c-common
kmod-rtl8192cu
kmod-rtlwifi
kmod-rtlwifi-usb
kmod-sched-cake
kmod-sched-core
kmod-scsi-core
kmod-slhc
kmod-thermal
kmod-tun
kmod-udptunnel4
kmod-udptunnel6
kmod-usb-core
kmod-usb-storage
kmod-usb-xhci-hcd
kmod-usb-xhci-mtk
kmod-usb3
kmod-wireguard
ksmbd-avahi-service
ksmbd-server
libatomic1
libavahi-dbus-support
libblkid1
libblobmsg-json20240126
libbpf1
libc
libcap-ng
libcomerr0
libcurl4
libdaemon
libdbus
libe2p2
libelf1
libevdev
libexpat
libext2fs2
libf2fs6
libgcc1
libgd
libgmp10
libiperf3
libiptext-nft0
libiptext0
libiptext6-0
libiwinfo-data
libiwinfo20230701
libjpeg-turbo
libjson-c5
libjson-script20240126
libltdl7
liblua5.1.5
liblucihttp-lua
liblucihttp-ucode
liblucihttp0
liblz4-1
liblzo2
libmbedtls13
libmnl0
libncurses6
libnetfilter-conntrack3
libnettle8
libnfnetlink0
libnftnl11
libnghttp2-14
libnl-core200
libnl-genl200
libnl-tiny1
libopenssl-conf
libopenssl-devcrypto
libopenssl-legacy
libopenssl3
libpcap1
libpng
libpthread
librrd1
librt
libsensors5
libsqlite3-0
libss2
libsysfs2
libubox20240126
libubus-lua
libubus20231128
libuci20130104
libuclient20201210
libucode20230711
libudebug
libudev-zero
libusb-1.0-0
libustream-mbedtls20201210
libuuid1
libwebp
libxtables12
lm-sensors
logd
lua
luci-app-adblock
luci-app-firewall
luci-app-irqbalance
luci-app-ksmbd
luci-app-openvpn
luci-app-opkg
luci-app-pbr
luci-app-sqm
luci-app-statistics
luci-app-vnstat2
luci-base
luci-compat
luci-lib-base
luci-lib-ip
luci-lib-jsonc
luci-lib-nixio
luci-lua-runtime
luci-mod-admin-full
luci-mod-network
luci-mod-status
luci-mod-system
luci-proto-3g
luci-proto-ppp
luci-proto-wireguard
luci-theme-bootstrap
mkf2fs
mt7986-wo-firmware
mtd
netifd
nftables-json
odhcp6c
odhcpd-ipv6only
openssl-util
openvpn-openssl
openwrt-keyring
opkg
pbr
ppp
ppp-mod-pppoe
procd
procd-seccomp
procd-ujail
resolveip
rpcd
rpcd-mod-file
rpcd-mod-iwinfo
rpcd-mod-luci
rpcd-mod-ucode
rrdtool1
rtl8192cu-firmware
sqm-scripts
sysfsutils
tc-tiny
tcpdump-mini
terminfo
ubi-utils
uboot-envtools
ubox
ubus
ubusd
uci
uclient-fetch
ucode
ucode-mod-fs
ucode-mod-html
ucode-mod-lua
ucode-mod-math
ucode-mod-nl80211
ucode-mod-rtnl
ucode-mod-ubus
ucode-mod-uci
ucode-mod-uloop
uhttpd
uhubctl
urandom-seed
urngd
usbids
usbutils
usign
vnstat2
vnstati2
wifi-scripts
wireguard-tools
wireless-regdb
wpad-basic-openssl
wsdd2
xtables-nft
zlib
```

Here is listed the diffconfig
```
CONFIG_TARGET_mediatek=y
CONFIG_TARGET_mediatek_filogic=y
CONFIG_TARGET_mediatek_filogic_DEVICE_glinet_gl-mt6000=y
CONFIG_DEVEL=y
CONFIG_BUSYBOX_CUSTOM=y
CONFIG_BUSYBOX_CONFIG_FEATURE_CROND_SPECIAL_TIMES=y
CONFIG_BUSYBOX_CONFIG_FEATURE_SYSLOG_INFO=y
CONFIG_BUSYBOX_CONFIG_FEATURE_TOP_INTERACTIVE=y
CONFIG_BUSYBOX_CONFIG_PKILL=y
CONFIG_GNUTLS_ALPN=y
CONFIG_GNUTLS_ANON=y
CONFIG_GNUTLS_DTLS_SRTP=y
CONFIG_GNUTLS_HEARTBEAT=y
CONFIG_GNUTLS_OCSP=y
CONFIG_GNUTLS_PSK=y
CONFIG_HTOP_LMSENSORS=y
CONFIG_IPK_FILES_CHECKSUMS=y
CONFIG_KEEPALIVED_CHECKSUM_COMPAT=y
CONFIG_KEEPALIVED_FWMARK=y
CONFIG_KEEPALIVED_IP6TABLES=y
CONFIG_KEEPALIVED_IPTABLES=y
CONFIG_KEEPALIVED_LINKBEAT=y
CONFIG_KEEPALIVED_LVS=y
CONFIG_KEEPALIVED_LVS_64BIT_STATS=y
CONFIG_KEEPALIVED_LVS_SYNCD=y
CONFIG_KEEPALIVED_NFTABLES=y
CONFIG_KEEPALIVED_ROUTES=y
CONFIG_KEEPALIVED_SHA1=y
CONFIG_KEEPALIVED_VRRP=y
CONFIG_KEEPALIVED_VRRP_AUTH=y
CONFIG_LIBCURL_COOKIES=y
CONFIG_LIBCURL_FILE=y
CONFIG_LIBCURL_FTP=y
CONFIG_LIBCURL_HTTP=y
CONFIG_LIBCURL_MBEDTLS=y
CONFIG_LIBCURL_NGHTTP2=y
CONFIG_LIBCURL_NO_SMB="!"
CONFIG_LIBCURL_PROXY=y
CONFIG_LIBCURL_UNIX_SOCKETS=y
CONFIG_LINUX_6_6=y
CONFIG_OPENSSL_ENGINE=y
CONFIG_OPENSSL_OPTIMIZE_SPEED=y
CONFIG_OPENSSL_WITH_ASM=y
CONFIG_OPENSSL_WITH_CHACHA_POLY1305=y
CONFIG_OPENSSL_WITH_CMS=y
CONFIG_OPENSSL_WITH_DEPRECATED=y
CONFIG_OPENSSL_WITH_ERROR_MESSAGES=y
CONFIG_OPENSSL_WITH_IDEA=y
CONFIG_OPENSSL_WITH_MDC2=y
CONFIG_OPENSSL_WITH_PSK=y
CONFIG_OPENSSL_WITH_SEED=y
CONFIG_OPENSSL_WITH_SRP=y
CONFIG_OPENSSL_WITH_TLS13=y
CONFIG_OPENSSL_WITH_WHIRLPOOL=y
CONFIG_OPENVPN_openssl_ENABLE_FRAGMENT=y
CONFIG_OPENVPN_openssl_ENABLE_LZ4=y
CONFIG_OPENVPN_openssl_ENABLE_LZO=y
CONFIG_OPENVPN_openssl_ENABLE_PORT_SHARE=y
CONFIG_OPENVPN_openssl_ENABLE_SMALL=y
CONFIG_PACKAGE_adblock=y
CONFIG_PACKAGE_adblock-fast=m
CONFIG_PACKAGE_attr=m
CONFIG_PACKAGE_avahi-dbus-daemon=y
CONFIG_PACKAGE_blkid=y
CONFIG_PACKAGE_block-mount=m
CONFIG_PACKAGE_blockd=m
CONFIG_PACKAGE_btrfs-progs=m
CONFIG_PACKAGE_ca-certificates=m
CONFIG_PACKAGE_cgi-io=y
CONFIG_PACKAGE_chat=y
CONFIG_PACKAGE_collectd=y
CONFIG_PACKAGE_collectd-mod-cpu=y
CONFIG_PACKAGE_collectd-mod-exec=m
CONFIG_PACKAGE_collectd-mod-interface=y
CONFIG_PACKAGE_collectd-mod-irq=m
CONFIG_PACKAGE_collectd-mod-iwinfo=y
CONFIG_PACKAGE_collectd-mod-load=y
CONFIG_PACKAGE_collectd-mod-memory=y
CONFIG_PACKAGE_collectd-mod-network=y
CONFIG_PACKAGE_collectd-mod-openvpn=m
CONFIG_PACKAGE_collectd-mod-rrdtool=y
CONFIG_PACKAGE_collectd-mod-sensors=y
CONFIG_PACKAGE_collectd-mod-sqm=m
CONFIG_PACKAGE_collectd-mod-thermal=m
CONFIG_PACKAGE_comgt=y
CONFIG_PACKAGE_containerd=m
CONFIG_PACKAGE_coreutils=y
CONFIG_PACKAGE_coreutils-sort=y
CONFIG_PACKAGE_coreutils-stat=y
CONFIG_PACKAGE_coreutils-timeout=m
CONFIG_PACKAGE_curl=y
CONFIG_PACKAGE_dbus=y
# CONFIG_PACKAGE_dnsmasq is not set
CONFIG_PACKAGE_dnsmasq-full=y
CONFIG_PACKAGE_dnsmasq_full_auth=y
CONFIG_PACKAGE_dnsmasq_full_conntrack=y
CONFIG_PACKAGE_dnsmasq_full_dhcp=y
CONFIG_PACKAGE_dnsmasq_full_dnssec=y
CONFIG_PACKAGE_dnsmasq_full_nftset=y
CONFIG_PACKAGE_dnsmasq_full_noid=y
CONFIG_PACKAGE_dnsmasq_full_tftp=y
CONFIG_PACKAGE_dockerd=m
CONFIG_PACKAGE_f2fs-tools=y
CONFIG_PACKAGE_hd-idle=m
CONFIG_PACKAGE_htop=m
CONFIG_PACKAGE_inotifywait=m
CONFIG_PACKAGE_ip-full=y
CONFIG_PACKAGE_ip6tables-nft=y
CONFIG_PACKAGE_iperf3=y
CONFIG_PACKAGE_iptables-mod-extra=m
CONFIG_PACKAGE_iptables-mod-ipopt=y
CONFIG_PACKAGE_iptables-mod-physdev=m
CONFIG_PACKAGE_iptables-nft=y
CONFIG_PACKAGE_ipvsadm=m
CONFIG_PACKAGE_irqbalance=y
CONFIG_PACKAGE_keepalived=m
CONFIG_PACKAGE_keepalived-sync=m
CONFIG_PACKAGE_kmod-asn1-decoder=y
CONFIG_PACKAGE_kmod-br-netfilter=m
CONFIG_PACKAGE_kmod-crypto-acompress=m
CONFIG_PACKAGE_kmod-crypto-crc32=y
CONFIG_PACKAGE_kmod-crypto-ecb=y
CONFIG_PACKAGE_kmod-crypto-geniv=y
CONFIG_PACKAGE_kmod-crypto-lib-chacha20=y
CONFIG_PACKAGE_kmod-crypto-lib-chacha20poly1305=y
CONFIG_PACKAGE_kmod-crypto-lib-curve25519=y
CONFIG_PACKAGE_kmod-crypto-lib-poly1305=y
CONFIG_PACKAGE_kmod-crypto-md4=y
CONFIG_PACKAGE_kmod-crypto-sha3=y
CONFIG_PACKAGE_kmod-cryptodev=y
CONFIG_PACKAGE_kmod-fs-autofs4=m
CONFIG_PACKAGE_kmod-fs-btrfs=m
CONFIG_PACKAGE_kmod-fs-exfat=y
CONFIG_PACKAGE_kmod-fs-ext4=y
CONFIG_PACKAGE_kmod-fs-f2fs=y
CONFIG_PACKAGE_kmod-fs-ksmbd=y
CONFIG_PACKAGE_kmod-fs-netfs=y
CONFIG_PACKAGE_kmod-fs-ntfs3=y
CONFIG_PACKAGE_kmod-fs-smbfs-common=y
CONFIG_PACKAGE_kmod-fs-vfat=y
CONFIG_PACKAGE_kmod-ifb=y
CONFIG_PACKAGE_kmod-ip6tables=y
CONFIG_PACKAGE_kmod-ipt-conntrack=m
CONFIG_PACKAGE_kmod-ipt-core=y
CONFIG_PACKAGE_kmod-ipt-extra=m
CONFIG_PACKAGE_kmod-ipt-ipopt=y
CONFIG_PACKAGE_kmod-ipt-ipset=m
CONFIG_PACKAGE_kmod-ipt-nat=m
CONFIG_PACKAGE_kmod-ipt-nat6=m
CONFIG_PACKAGE_kmod-ipt-physdev=m
CONFIG_PACKAGE_kmod-lib-crc16=y
CONFIG_PACKAGE_kmod-lib-lzo=m
CONFIG_PACKAGE_kmod-lib-raid6=m
CONFIG_PACKAGE_kmod-lib-xor=m
CONFIG_PACKAGE_kmod-lib-zlib-deflate=m
CONFIG_PACKAGE_kmod-lib-zlib-inflate=m
CONFIG_PACKAGE_kmod-lib-zstd=m
# CONFIG_PACKAGE_kmod-libphy is not set
CONFIG_PACKAGE_kmod-macvlan=m
CONFIG_PACKAGE_kmod-mii=m
CONFIG_PACKAGE_kmod-nf-conntrack-netlink=y
CONFIG_PACKAGE_kmod-nf-ipt=y
CONFIG_PACKAGE_kmod-nf-ipt6=y
CONFIG_PACKAGE_kmod-nf-ipvs=m
CONFIG_PACKAGE_kmod-nf-nat6=m
CONFIG_PACKAGE_kmod-nft-compat=y
CONFIG_PACKAGE_kmod-nls-cp437=y
CONFIG_PACKAGE_kmod-nls-iso8859-1=y
CONFIG_PACKAGE_kmod-nls-ucs2-utils=y
CONFIG_PACKAGE_kmod-nls-utf8=y
CONFIG_PACKAGE_kmod-oid-registry=y
# CONFIG_PACKAGE_kmod-phy-aquantia is not set
CONFIG_PACKAGE_kmod-rtl8192c-common=y
CONFIG_PACKAGE_kmod-rtl8192cu=y
CONFIG_PACKAGE_kmod-rtlwifi=y
CONFIG_PACKAGE_kmod-rtlwifi-usb=y
CONFIG_PACKAGE_kmod-sched-cake=y
CONFIG_PACKAGE_kmod-sched-core=y
CONFIG_PACKAGE_kmod-scsi-core=y
CONFIG_PACKAGE_kmod-tun=y
CONFIG_PACKAGE_kmod-udptunnel4=y
CONFIG_PACKAGE_kmod-udptunnel6=y
CONFIG_PACKAGE_kmod-usb-net=m
CONFIG_PACKAGE_kmod-usb-net-cdc-eem=m
CONFIG_PACKAGE_kmod-usb-net-cdc-ether=m
CONFIG_PACKAGE_kmod-usb-net-cdc-ncm=m
CONFIG_PACKAGE_kmod-usb-net-cdc-subset=m
CONFIG_PACKAGE_kmod-usb-net-huawei-cdc-ncm=m
CONFIG_PACKAGE_kmod-usb-net-ipheth=m
CONFIG_PACKAGE_kmod-usb-net-rndis=m
CONFIG_PACKAGE_kmod-usb-storage=y
CONFIG_PACKAGE_kmod-usb-wdm=m
CONFIG_PACKAGE_kmod-veth=m
CONFIG_PACKAGE_kmod-wireguard=y
CONFIG_PACKAGE_ksmbd-avahi-service=y
CONFIG_PACKAGE_ksmbd-hotplug=m
CONFIG_PACKAGE_ksmbd-server=y
CONFIG_PACKAGE_libatomic=y
CONFIG_PACKAGE_libattr=m
CONFIG_PACKAGE_libavahi-client=m
CONFIG_PACKAGE_libavahi-dbus-support=y
CONFIG_PACKAGE_libbpf=y
CONFIG_PACKAGE_libbz2=m
CONFIG_PACKAGE_libcap=m
CONFIG_PACKAGE_libcap-ng=y
CONFIG_PACKAGE_libcurl=y
CONFIG_PACKAGE_libdaemon=y
CONFIG_PACKAGE_libdbus=y
CONFIG_PACKAGE_libelf=y
CONFIG_PACKAGE_libevdev=y
CONFIG_PACKAGE_libexif=m
CONFIG_PACKAGE_libexpat=y
CONFIG_PACKAGE_libffmpeg-audio-dec=m
CONFIG_PACKAGE_libflac=m
CONFIG_PACKAGE_libgd=y
CONFIG_PACKAGE_libgmp=y
CONFIG_PACKAGE_libgnutls=m
CONFIG_PACKAGE_libid3tag=m
CONFIG_PACKAGE_libimobiledevice=m
CONFIG_PACKAGE_libinotifytools=m
CONFIG_PACKAGE_libip4tc=m
CONFIG_PACKAGE_libip6tc=m
CONFIG_PACKAGE_libiperf3=y
CONFIG_PACKAGE_libipset=m
CONFIG_PACKAGE_libiptext=y
CONFIG_PACKAGE_libiptext-nft=y
CONFIG_PACKAGE_libiptext6=y
CONFIG_PACKAGE_libjpeg-turbo=y
CONFIG_PACKAGE_libkmod=m
CONFIG_PACKAGE_libltdl=y
CONFIG_PACKAGE_liblua=y
CONFIG_PACKAGE_liblucihttp=y
CONFIG_PACKAGE_liblucihttp-lua=y
CONFIG_PACKAGE_liblucihttp-ucode=y
CONFIG_PACKAGE_liblz4=y
CONFIG_PACKAGE_liblzma=m
CONFIG_PACKAGE_liblzo=y
CONFIG_PACKAGE_libmagic=m
CONFIG_PACKAGE_libmount=m
CONFIG_PACKAGE_libncurses=y
CONFIG_PACKAGE_libnetfilter-conntrack=y
CONFIG_PACKAGE_libnettle=y
CONFIG_PACKAGE_libnfnetlink=y
CONFIG_PACKAGE_libnghttp2=y
CONFIG_PACKAGE_libnl-core=y
CONFIG_PACKAGE_libnl-genl=y
CONFIG_PACKAGE_libnl-route=m
CONFIG_PACKAGE_libogg=m
CONFIG_PACKAGE_libopenssl=y
CONFIG_PACKAGE_libopenssl-conf=y
CONFIG_PACKAGE_libopenssl-devcrypto=y
CONFIG_PACKAGE_libopenssl-legacy=y
CONFIG_PACKAGE_libpcap=y
CONFIG_PACKAGE_libplist=m
CONFIG_PACKAGE_libpng=y
CONFIG_PACKAGE_libpopt=m
CONFIG_PACKAGE_libqrencode=m
CONFIG_PACKAGE_libreadline=m
CONFIG_PACKAGE_librrd1=y
CONFIG_PACKAGE_libseccomp=m
CONFIG_PACKAGE_libsensors=y
CONFIG_PACKAGE_libsmartcols=m
CONFIG_PACKAGE_libsqlite3=y
CONFIG_PACKAGE_libsysfs=y
CONFIG_PACKAGE_libtasn1=m
CONFIG_PACKAGE_libtirpc=m
CONFIG_PACKAGE_libubus-lua=y
CONFIG_PACKAGE_libudev-zero=y
CONFIG_PACKAGE_liburing=m
CONFIG_PACKAGE_libusb-1.0=y
CONFIG_PACKAGE_libusbmuxd=m
CONFIG_PACKAGE_libvorbis=m
CONFIG_PACKAGE_libwebp=y
CONFIG_PACKAGE_libxml2=m
CONFIG_PACKAGE_libxtables=y
CONFIG_PACKAGE_lm-sensors=y
CONFIG_PACKAGE_lsblk=m
CONFIG_PACKAGE_lua=y
CONFIG_PACKAGE_luci-app-adblock=y
CONFIG_PACKAGE_luci-app-adblock-fast=m
CONFIG_PACKAGE_luci-app-firewall=y
CONFIG_PACKAGE_luci-app-hd-idle=m
CONFIG_PACKAGE_luci-app-irqbalance=y
CONFIG_PACKAGE_luci-app-keepalived=m
CONFIG_PACKAGE_luci-app-ksmbd=y
CONFIG_PACKAGE_luci-app-minidlna=m
CONFIG_PACKAGE_luci-app-openvpn=y
CONFIG_PACKAGE_luci-app-opkg=y
CONFIG_PACKAGE_luci-app-pbr=y
CONFIG_PACKAGE_luci-app-samba4=m
CONFIG_PACKAGE_luci-app-sqm=y
CONFIG_PACKAGE_luci-app-statistics=y
CONFIG_PACKAGE_luci-app-upnp=m
CONFIG_PACKAGE_luci-app-vnstat2=y
CONFIG_PACKAGE_luci-app-wifischedule=m
CONFIG_PACKAGE_luci-base=y
CONFIG_PACKAGE_luci-compat=y
CONFIG_PACKAGE_luci-lib-base=y
CONFIG_PACKAGE_luci-lib-ip=y
CONFIG_PACKAGE_luci-lib-jsonc=y
CONFIG_PACKAGE_luci-lib-nixio=y
CONFIG_PACKAGE_luci-lua-runtime=y
CONFIG_PACKAGE_luci-mod-admin-full=y
CONFIG_PACKAGE_luci-mod-network=y
CONFIG_PACKAGE_luci-mod-status=y
CONFIG_PACKAGE_luci-mod-system=y
CONFIG_PACKAGE_luci-proto-3g=y
CONFIG_PACKAGE_luci-proto-ipv6=m
CONFIG_PACKAGE_luci-proto-ppp=y
CONFIG_PACKAGE_luci-proto-wireguard=y
CONFIG_PACKAGE_luci-theme-bootstrap=y
CONFIG_PACKAGE_minidlna=m
CONFIG_PACKAGE_miniupnpd-nftables=m
CONFIG_PACKAGE_openssl-util=y
CONFIG_PACKAGE_openvpn-openssl=y
CONFIG_PACKAGE_pbr=y
CONFIG_PACKAGE_qrencode=m
CONFIG_PACKAGE_resolveip=y
CONFIG_PACKAGE_rpcd=y
CONFIG_PACKAGE_rpcd-mod-file=y
CONFIG_PACKAGE_rpcd-mod-iwinfo=y
CONFIG_PACKAGE_rpcd-mod-luci=y
CONFIG_PACKAGE_rpcd-mod-ucode=y
CONFIG_PACKAGE_rrdtool1=y
CONFIG_PACKAGE_rsync=m
CONFIG_PACKAGE_rtl8192cu-firmware=y
CONFIG_PACKAGE_runc=m
CONFIG_PACKAGE_samba4-libs=m
CONFIG_PACKAGE_samba4-server=m
CONFIG_PACKAGE_sqm-scripts=y
CONFIG_PACKAGE_sudo=m
CONFIG_PACKAGE_sysfsutils=y
CONFIG_PACKAGE_tc-tiny=y
CONFIG_PACKAGE_tcpdump-mini=y
CONFIG_PACKAGE_terminfo=y
CONFIG_PACKAGE_tini=m
CONFIG_PACKAGE_ucode-mod-html=y
CONFIG_PACKAGE_ucode-mod-lua=y
CONFIG_PACKAGE_ucode-mod-math=y
CONFIG_PACKAGE_uhttpd=y
CONFIG_PACKAGE_uhubctl=y
CONFIG_PACKAGE_usbids=y
CONFIG_PACKAGE_usbmuxd=m
CONFIG_PACKAGE_usbutils=y
CONFIG_PACKAGE_vnstat2=y
CONFIG_PACKAGE_vnstati2=y
CONFIG_PACKAGE_wifischedule=m
CONFIG_PACKAGE_wireguard-tools=y
# CONFIG_PACKAGE_wpad-basic-mbedtls is not set
CONFIG_PACKAGE_wpad-basic-openssl=y
CONFIG_PACKAGE_wsdd2=y
CONFIG_PACKAGE_xtables-nft=y
CONFIG_PACKAGE_zlib=y
CONFIG_SAMBA4_SERVER_AVAHI=y
CONFIG_SAMBA4_SERVER_NETBIOS=y
CONFIG_SAMBA4_SERVER_VFS=y
CONFIG_SAMBA4_SERVER_WSDD2=y
CONFIG_SQLITE3_COLUMN_METADATA=y
CONFIG_SQLITE3_DYNAMIC_EXTENSIONS=y
CONFIG_SQLITE3_FTS3=y
CONFIG_SQLITE3_FTS4=y
CONFIG_SQLITE3_FTS5=y
CONFIG_SQLITE3_RTREE=y
CONFIG_TARGET_OPTIMIZATION="-O2 -pipe -mcpu=cortex-a53"
CONFIG_TARGET_OPTIONS=y
CONFIG_TESTING_KERNEL=y
# CONFIG_PACKAGE_dnsmasq_full_dhcpv6 is not set
# CONFIG_PACKAGE_kmod-crypto-kpp is not set
```
