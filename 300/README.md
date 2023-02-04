# 300 - Building Our Application

## 100 - Installation

**Schematics Shelly Pro 4 PM**

![Schematics_Shelly_Pro_4_PM](https://user-images.githubusercontent.com/1499433/215257673-45718852-37a3-4548-8a2d-fc2dd3304a19.png)

Fig. 1

Video: [How to start a Smart Home with Shelly Pro 4PM - Step by Step tutorial](https://www.youtube.com/watch?v=xbiQFFJl9A4)

We follow the instructions as provided in above video:

1) Remove the plastic covers (covering 04 03 L 02 01, and LAN N S4 S3 S2 S1) from the Shelly Pro 4 PM, that protect the connectors, by means of a flat screwdriver.

2) **IMPORTANT**: Switch off the main power before you proceed so there is **no power** in the metering cabinet. In addition, turn all fuse breakers to OFF before removing the lid of the cabinet(s).

3) Inside the metering cabinet in your home, remove the lid that covers your rails, onto which the Shelly Pro 4 PM will be attached.

4) Also remove any covering that prevents the Shelly Pro 4 PM from being visible after the cover has been put back in place.

5) In case the metering cabinet does not have openings where we could lead the Ethernet cable through (to be connected with the WiFi router later on), look for pre-made cutouts that allow us to cutout such an opening by applying pressure. This way allow for the Ethernet cable to exit the metering cabinet.

5) Place the Shelly Pro 4 PM onto the rails, with the text facing up, by slightly pullling the release down and clipping it onto the rails. The release should fasten the Shelly Pro 4 PM to the rails.

6) ...

|Terminal ID|Wire (Color)|Connect TO|Comment|
|--|--|--|--|
|LAN|Ethernet Cable|Modem|To connect the Shelly to the local area network|
|N - Neutral terminal|Neutral/Nuldraad/Neutre (Blue) Max. 9200 watt, 6mm2|Neutral cable in the metering cabinet, that lets the power go out.|

MORE ...



ADDITIONAL VIDEOS:

Video: [Shelly Pro 4PM // How to Install & Use](https://www.youtube.com/watch?v=vZQEg2qjwRk)

-- Official Installation Instructions --

Connect the relay to the power grid and install it in the switchboard as shown in the scheme (fig. 1) and following the Safety Instructions. Before installing/mounting 
the device, ensure that the grid is powered off (turned down breakers) and in compliance with the Safety Norms.

The Shelly Pro 4PM smart relay by Allterco Robotics is intended to be mounted into a standard switchboard on DIN rail, next to the circuit breakers in order to control and 
monitor the electric power through it. Shelly can work as a standalone device or as an accessory to a home automation controller.

Before starting, wire check that the breakers are turned off and there is no voltage on their terminals. This can be done with a phase meter or multimeter. When you are 
sure that there is no voltage, you can start wiring the cables according to fig.1. Install a wire from O1, O2, O3, O4 - to the load and from the load to the Neutral. Install also 
a wire from the Fuse to L.

Connect the Neutral to the device. The last step is to install cables from the switches to the terminals S1, S2, S3 and S4.

For inductive appliances, those that cause voltage spikes during switching on: electrical motors, as fans, vacuum cleaners and similar ones, RC snubber (0.1µF / 100Ω / 
1/2W / 600V AC) should be wired between Output and Neutral of the circuit.

**⚠ CAUTION!** Do not install the device at a place that is possible to get wet.

**⚠ CAUTION!** Danger of electrocution. Mounting/ Installation of the Device to the power grid has to be performed with caution, by a qualified person (electrician).

**⚠ CAUTION!** Danger of electrocution. Mounting the Device to the power grid has to be performed with caution.

**⚠ CAUTION!** Do not allow children to play with the button/switch connected to the Device. Keep the Devices for remote control of Shelly (mobile phones, tablets, PCs) away 
from children.

**⚠ CAUTION!** Danger of electrocution. Even when the Device is turned off, it is possible to have voltage across its terminals. Every change in the connection of the terminals 
has to be done after ensuring all local power is powered off/disconnected.

**⚠ CAUTION!** Do not connect the Device to appliances exceeding the given max load!

**⚠ CAUTION!** Use the Device only with a power grid and appliances which comply with all applicable regulations. A short circuit in the power grid or any appliance connected 
to the Device may damage the Device.

**⚠ CAUTION!** Connect the Device only in the way shown in hese instructions. Any other method could cause damage and/or injury.

**⚠ RECOMMENDATION!** Тhe Device may be connected to and may control electric circuits and appliances only if they comply with the respective standards and safety norms.

**⚠ RECOMMENDATION!** The Device may be connected with solid single-core cables with increased heat resistance to insulation not less than PVC T105°C.

## Accessing the Shelly Pro 4 PM

Shelly® is a line of innovative Devices, which allow remote control of electric appliances through a mobile phone, tablet, PC, or home automation system. Shelly® 
may work standalone on the local Wi-Fi network, without being managed by a home automation controller, or it can also work through cloud home automation services. 

Shelly® devices can be accessed, controlled, and monitored remotely from any place the User has Internet connectivity, as long as the devices are connected to a Wi-Fi 
router and the Internet.

Shelly® has an integrated web server, through which the User may adjust, control and monitor the Device. The web interface is accessible at http://192.168.33.1

Shelly® has two Wi-Fi modes - access Point (AP) and Client mode (CM). To operate in Client Mode, a Wi-Fi router must be located within the range of the Device. Shelly® devices can communicate directly with other Wi-Fi devices through HTTPS protocol. An API can be provided by the Manufacturer.

Shelly® devices may be available for monitor and control even if the User is outside the range of the local Wi-Fi network, as long as the Wi-Fi router is connected to the Internet. The cloud function could be used, which is activated through the web server of the Device or through the settings in the Shelly Cloud mobile application.

The User can register and access Shelly Cloud, using either Android or iOS mobile applications, or any internet browser and the website: https://my.Shelly.cloud/ 



