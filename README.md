We Work Detok Not Only Tok Detok

echo -e "net.ipv6.conf.all.disable_ipv6 = 1\nnet.ipv6.conf.default.disable_ipv6 = 1\nnet.ipv6.conf.lo.disable_ipv6 = 1" >> /etc/sysctl.conf && sysctl -p

apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo lsof socat net-tools bc coreutils build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot

screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/install.sh && chmod +x install.sh && ./install.sh; read -p 'Tekan enter untuk keluar...'"

Perintah Update Script

wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/update.sh && chmod +x update.sh && ./update.sh && rm -f update.sh

screen -r -d setup

UDP CUSTOM

wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/udepe.sh && chmod +x udepe.sh && ./udepe.sh && rm -f udepe.sh

CLEAR INSTALLER SCRIPT IN YOUR VPS THANKS FOR BIN456789

rebuild deb 10 selain do

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 10 && reboot</code></pre>  rebuild debian 11

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 11 && reboot</code></pre>  rebuild debian 12

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 12 && reboot</code></pre>  rebuild debian 13

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 13 && reboot</code></pre>  rebuild ubuntu 20.04

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 20.04 && reboot</code></pre>  rebuild ubuntu 22

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 22.04 && reboot</code></pre>  rebuild ubuntu 24

<pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 24.04 && reboot</code></pre>  Rebuild ubuntu 25

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 25.04 && reboot

Apt Update



apt update && apt install curl -y

apt-get update && apt-get install wget -y

Installation

2.installation script:

wget "https://raw.githubusercontent.com/Ris-Project/x-only/main/install2.sh" -O install2.sh && chmod +x install2.sh && bash install2.sh

buatkn httml buat Redame.md    .note{background:#082033;padding:8px;border-radius:8px;color:#bcd6f6}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    @media(max-width:720px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="container">
    <h1>README — Ris-Project / UDP CUSTOM</h1>
    <p>Dokumentasi singkat dan kumpulan perintah untuk memasang, memperbarui, dan mereset installer pada VPS.</p><div class="section">
  <h2>Pengaturan IPv6 (Disable)</h2>
  <pre><code>echo -e "net.ipv6.conf.all.disable_ipv6 = 1\nnet.ipv6.conf.default.disable_ipv6 = 1\nnet.ipv6.conf.lo.disable_ipv6 = 1" &gt;&gt; /etc/sysctl.conf && sysctl -p</code></pre>
</div>

<div class="section">
  <h2>Update &amp; Upgrade Sistem</h2>
  <pre><code>apt update -y && apt upgrade -y --fix-missing \

&& apt install -y xxd bzip2 wget curl sudo lsof socat net-tools bc coreutils build-essential bsdmainutils screen dos2unix 
&& update-grub && apt dist-upgrade -y && sleep 2 && reboot</code></pre> </div>

<div class="section">
  <h2>Menjalankan Installer di screen</h2>
  <pre><code>screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/install.sh && chmod +x install.sh && ./install.sh; read -p 'Tekan enter untuk keluar...'"</code></pre>
  <p class="note">Gunakan <code>screen -r -d setup</code> untuk meng-attach session jika diperlukan.</p>
</div>

<div class="section">
  <h2>Perintah Update Script</h2>
  <pre><code>wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/update.sh && chmod +x update.sh && ./update.sh && rm -f update.sh</code></pre>
</div>

<div class="section">
  <h2>UDP CUSTOM</h2>
  <pre><code>wget -q https://raw.githubusercontent.com/Ris-Project/x-only/main/udepe.sh && chmod +x udepe.sh && ./udepe.sh && rm -f udepe.sh</code></pre>

  <p>Tambahan: <strong>Clear installer script</strong> dari BIN456789 untuk rebuild/downgrade/upgrade sistem operasi.</p>
  <div class="grid">
    <div>
      <h3>Rebuild Debian / Ubuntu</h3>
      <pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 10 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 11 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 12 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh debian 13 && reboot</code></pre> </div> <div> <h3>Rebuild Ubuntu (varian)</h3> <pre><code>curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 20.04 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 22.04 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 24.04 && reboot

curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 25.04 && reboot</code></pre> </div> </div> </div>

<div class="section">
  <h2>Apt Update Singkat</h2>
  <pre><code>apt update && apt install curl -y

apt-get update && apt-get install wget -y</code></pre> </div>

<div class="section">
  <h2>Installer Alternatif (install2.sh)</h2>
  <pre><code>wget "https://raw.githubusercontent.com/Ris-Project/x-only/main/install2.sh" -O install2.sh && chmod +x install2.sh && bash install2.sh</code></pre>
</div>

<div class="section">
  <h2>Catatan &amp; Tips</h2>
  <ul>
    <li>Jalankan perintah sebagai <code>root</code> atau gunakan <code>sudo</code> jika perlu.</li>
    <li>Sebelum reboot secara otomatis, pastikan konfigurasi jaringan dan SSH sudah benar untuk menghindari kehilangan akses.</li>
    <li>Periksa URL skrip yang diunduh untuk memastikan sumber tepercaya.</li>
  </ul>
</div>

<div class="section">
  <h2>Lisensi &amp; Penghargaan</h2>
  <p class="note">Terima kasih kepada <strong>BIN456789</strong> dan <strong>Ris-Project</strong> untuk skrip dan tooling.</p>
</div>

<footer style="margin-top:18px;color:#88b6e0;font-size:13px">Generated: README HTML — untuk disimpan sebagai <code>README.html</code></footer>

  </div>
</body>
</html>
