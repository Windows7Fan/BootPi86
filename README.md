# BootPi86
<h6>A project that allows booting x86_64 OS's on a RPI using QEMU.</h6>

<img src="BootPi86.png" alt="BootPi86 Logo" width="240" height="240">

<h2>Things to expect:</h2>
<h6>A slow computer</h6>


<h2>Supported physical boot devices:</h2>
<h6>USB CD-ROM/DVD Drive</h6>
<h6>a USB drive</h6>





<h2>Tested RPI's:</h2>
<h6>Raspberry Pi 4 Model B</h6>
<h6>Raspberry Pi 400</h6>


<h2>Not Tested Raspberry Pi's but should work in theory:</h2>
<h6>Raspberry Pi 5</h6>
<h6>Raspberry Pi 500</h6>
<h6>Raspberry Pi 3 (Maybe??)</h6>




<h2>How to resize the QEMU disk image</h2>
<h6>Step 1: Boot the Pi</h6>
<h6>Step 2: Press Ctrl+Alt+F to get out of fullscreen mode in qemu</h6>
<h6>Step 3: Right click on the desktop and click "Exit"</h6>
<h6>Step 4: Type "sudo qemu-img resize ./disk.qcow2 10G" Replace the 10 with whatever number you would like in GB (dont get rid of the G)</h6>
<h6>Step 5: Reboot the Pi</h6>
<h6>Default Size is 32G</h6>




<h2>MAKE SURE TO HAVE THESE SETTINGS:</h2>
<img src="make sure.png" width="218" height="252">
