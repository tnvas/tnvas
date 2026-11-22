<table>
  <tr>
    <td width="62%" valign="top">
      <h2>tnvas</h2>
      <p>Technician during the day, building software at night.</p>
      <p>At work I'm usually the one with a laptop plugged into a machine, trying to find out why it stopped. That habit carried over: when something at home or on the bench annoys me enough, I write a tool for it. Go is my default. Python and C show up when a driver or a vendor library asks for them.</p>
      <p>A good part of what's here is built with AI agents doing the heavy lifting while I steer, test and fix. I don't hide that, and I don't publish anything I haven't used myself.</p>
      <p><b>Currently poking at:</b> WebXR performance on the Quest, and Fyne layouts that don't fall apart on small screens.</p>
    </td>
    <td width="38%" valign="top" align="center">
      <br/>
      <img src="https://skillicons.dev/icons?i=go,py,c,bash,linux,docker,sqlite,js,threejs,git,githubactions,vscode&perline=4" alt="Tech I use" />
    </td>
  </tr>
</table>
<h2>On the workbench</h2>
 
<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tnvas/wgAdmin"><img src="https://github.com/tnvas/wgAdmin/raw/main/docs/screenshots/main-dark.png" alt="wgAdmin main window" /></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tnvas/wgAdmin">wgAdmin</a> <sub><code>Go</code> <code>Fyne</code></sub></h3>
      <p>WireGuard management for people who'd rather click than edit config files. Tunnels, peers, live traffic, QR codes for phones, a network scanner, and automatic backups before anything gets changed.</p>
<pre>make build
sudo ./build/usr/local/bin/wgAdmin</pre>
      <a href="https://github.com/tnvas/wgAdmin"><img src="https://github.com/tnvas/wgAdmin/raw/main/docs/screenshots/qr.png" alt="QR code for a peer" width="62%" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tnvas/VRStreamDeck"><img src="https://github.com/tnvas/VRStreamDeck/raw/main/docs/screenshots/vr-cinema.png" alt="Cinema mode in VRStreamDeck" /></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tnvas/VRStreamDeck">VRStreamDeck</a> <sub><code>Go</code> <code>WebXR</code> <code>Three.js</code></sub></h3>
      <p>Your own VR and 360° video library, streamed from a home server to a Meta Quest. It figures out the projection and 3D layout by itself, generates thumbnails and seek previews, and lets you fix anything it gets wrong from inside the headset. One binary, nothing in the cloud.</p>
<pre>./vrstreamdeck -videos ~/Videos/vr
# open https://&lt;your-ip&gt;:8443
# in the Quest browser</pre>
      <a href="https://github.com/tnvas/VRStreamDeck"><img src="https://github.com/tnvas/VRStreamDeck/raw/main/docs/screenshots/vr-library.png" alt="Library menu inside VR" width="62%" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/tnvas/FutekUsb_DesktopUI"><img src="https://github.com/tnvas/FutekUsb_DesktopUI/raw/main/docs/screenshots/live.png" alt="UsbSens3 live view" /></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tnvas/FutekUsb_DesktopUI">UsbSens3</a> <sub><code>Go</code> <code>Fyne</code></sub></h3>
      <p>Desktop recorder for FUTEK force sensors on the USB220 adapter. Big live readout with min, max and average, a scrolling chart, tare and unit switching. Recordings go into SQLite and can be exported as CSV or a chart image. Runs on Linux and Windows.</p>
<pre>make sim   # no sensor? use the simulator
make app   # Linux build
make win_build</pre>
      <a href="https://github.com/tnvas/FutekUsb_DesktopUI"><img src="https://github.com/tnvas/FutekUsb_DesktopUI/raw/main/docs/screenshots/recordings.png" alt="UsbSens3 recordings view" width="62%" /></a>
    </td>
  </tr>
</table>
<h2>Fresh off the bench</h2>
 
<!-- PROJECTS:START -->
| Project | What it does | Stack |
|---|---|---|
| [**FutekUsb_DesktopUI**](https://github.com/tnvas/FutekUsb_DesktopUI) | Simple GUI to record from a Futek USB220 device to csv files with the option to export recording as a graph (image) | `Go` |
| [**VRStreamDeck**](https://github.com/tnvas/VRStreamDeck) | HTTPS webserver for localhosting VR videos to Quest and other VR devices | `JavaScript` |
| [**wgAdmin**](https://github.com/tnvas/wgAdmin) | A Linux based wireguard GUI for managing wireguard configs. | `Go` |
<!-- PROJECTS:END -->
 
<br/>
<p align="center"><sub>Issues and pull requests welcome on all of these 🔧</sub></p>
 
