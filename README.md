Prominent Operating System
==========================

## Bad for the web. Good for writing software.

Prominent OS aims to ease the burden of developing highly-available
software for an environment with embedded devices, laptops, servers and
industrial automation.

This is an internal operating system project for Prominent Research and 
Development that we recognize could be desirable for other teams. 

We are not here to make yet another POSIX-compliant Linux-alike. This is
completely new, with some new ways (and some forgotten and old ways) to 
to think about developing software.

We develop products for large networks of equipment of varying scale:

- small microcontrollers with only serial or SPI communication
- IoT devices with serial, zigbee
- Single-board computers with Ethernet and WiFi
- Industrial PLCs with modbus, EtherCAT, and Canbus.
- Entertainment show controllers with DMX, MIDI and GPIO
- Mobile robots that have multiple systems integrated onboard

Creating software that is aware of the complicated topologies that these
environments often require is usually rather challenging.

Prominent OS makes discovering and communicating with all devices, no matter 
where they are located or what they are connected to, and has a tool that makes
used to visualize and diagnose such an environment.

Prominent OS can schedule work to meet hard-realtime deadlines, which we use
for audio processing, safety, and motion control.



_"Bad for the web"_ is both a promise and a threat. 

The web is a terrible environment on which to develop and use software.
It has become a convoluted mess of open-source dependencies that most developers
don't understand, but use anyway.

Do not expect to ever see ports of Apache, Python, Mongo or MySQL here.

So Prominent OS would be a poor choice to use in your typical datacenter role.

However, we have plans to offer a compelling alternative to the web experience,
and will be making announcements about that sometime next year.

