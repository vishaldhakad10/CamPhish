# ReconEye
Grab cam shots from target's phone front camera or PC webcam just sending a link.

# What is ReconEye?
<p>ReconEye is a technique used to capture camera snapshots from a phone's front camera or a PC webcam. ReconEye hosts a website on an in-built PHP server and uses Ngrok and Cloudflare Tunnel to generate a shareable link. The website requests camera permission, and if permission is granted, the tool captures camera snapshots from the device.</p>
<p>A GPS location capture feature has also been added.</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
  <li>Online Meeting [Beta]</li>
  <li>GPS Location Tracking</li>
</ul>
<p>A cleanup script has been added to remove all unnecessary files and logs.</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
  <li>Windows (WSL)</li>
</ul>

# Installing and requirements
<p>This tool requires PHP for the web server and wget for downloading dependencies. First run following command on your terminal</p>

```
apt-get -y install php wget unzip
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/vishaldhakad10/ReconEye.git
cd ReconEye
bash reconeye.sh
```

## Clean logs & unnecessary files :

```
bash cleanup.sh
```
<p>The cam files and saved location will also be removed.</p>

## Change Log:

<p><b>Version: 2.0:</b> Added GPS Location Tracking</p>
<ul>
  <li>Added: GPS location capturing functionality</li>
  <li>Added: Google Maps integration for captured locations</li>
  <li>Added: Location accuracy reporting</li>
  <li>Added: Improved loading screen with location request</li>
</ul>

<p><b>Version: 1.9:</b> Enhanced architecture detection</p>
<ul>
  <li>Added: Improved architecture detection for all CPU types</li>
  <li>Added: Better support for Apple Silicon (M1/M2/M3) Macs</li>
  <li>Added: Automatic detection of ARM, ARM64, x86, and x86_64 architectures</li>
  <li>Fixed: Windows compatibility improvements</li>
  <li>Fixed: CloudFlare Tunnel download issues</li>
</ul>

<p><b>Version: 1.8:</b> Added CloudFlare Tunnel and removed Serveo</p>
<ul>
  <li>Added: CloudFlare Tunnel support for more reliable connections</li>
  <li>Removed: Serveo tunnel (deprecated)</li>
  <li>Fixed: Various code improvements and bug fixes</li>
</ul>

<p><b>Version: 1.7:</b> Fix and add support</p>
<ul>
  <li>fixed: termux failed to get home directory</li>
  <li>Add support for Apple Sillicon (M1/M2/M3 ARM64)</li>
  <li>Add support for arm64 like Raspberry Pi</li>
</ul>
<p><b>Version: 1.6:</b> Fix ngrok direct link generate</p>
<p><b>Version: 1.5:</b> Add new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>

### Important Notice
Unauthorized reuploading of this project is prohibited.

