<header>
  <h1>Cyclocopter Control System</h1>
</header>

Using an SBUS reciever and MPU6050 accelerometer, this version of <a href="dRehm Flight">https://github.com/nickrehm/dRehmFlight</a> 
is currently being updated to work for an cyclocopter at part of a projec with AeroNU's UAV division. Built with a Teensy 3.6, SBUS reciever, and uses a FRSKY controller.

Key notes of major changes from the original dRehm Flight:
<ul>
  <li>SBUS: Updated the "SBUS_caps" library to compose an SbusRx object from the "sbus" library as a hopeful means of sucessful connection.</li>
  <li>Pinout: Should be accurate for a pinout of a very specific drone in the FR244. If not, can easily be updated using <a href="Teensy 3.6 pinout">https://www.pjrc.com/store/teensy36.html</a>.</li>
</ul>
