<h5>An example of connection between Chrome and Arduino through a serial port</h5>
<p>
    You can use stable usb connection between cheap Arduino nano board (or one of it's clones) and your
    computer / phone / tablet with google chrome browser for home automatization, getting sensors data etc.
</p>
<p>
    <ol>
        <li>Connect your arduino to computer through USB and upload scetch.ino to it, check that arduino respond to your commands in arduino IDE built in serial port</li>
        <li>The solution is based on the <a href="https://wicg.github.io/serial/">Serial API</a> technology,
                with now still not enabled by default. To enable it, go to 
                <a href="chrome://flags/#enable-experimental-web-platform-features">chrome://flags/#enable-experimental-web-platform-features</a> and turn on the option "Experimental Web Platform features".</li>
        <li>Open index.html in your browser through https protocol, select port and try to interact with arduino. If there are no arduino port in list, try to reconnect it.</li>
    </ol>
</p>
