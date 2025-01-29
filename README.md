<h3>OpenRacer - An open source frame with 3D printed canopy for racing and freestyle.</h3>
<hr>

<h3>Support OpenRacer</h3>

If you would like to support the development of OpenRacer please feel free to make a small [donation](https://www.paypal.com/donate/?business=BUEQ8JBU8M42U&no_recurring=0&item_name=Support+OpenRacer+FPV+Frame+Design&currency_code=USD). This helps us pay for prototyping/testing of carbon and canopies. When you donate, feel free to leave a comment what additions would you like to see next.

[DONATE](https://www.paypal.com/donate/?business=BUEQ8JBU8M42U&no_recurring=0&item_name=Support+OpenRacer+FPV+Frame+Design&currency_code=USD)

Full frame kits are sold by [Five33](https://flyfive33.com/products/five33-open-racer-frame-kit-1?wpam_id=17) (aff. link). You can also order the carbon from [CNC Madness](https://cncmadness.com/). We provide instructions for printing your own canopy, but if you would like one printed we recommend [Phoenix 3D](https://www.phx-3d.com/). Carbon files are for 5 inch props unless otherwise specified.

<h3>Useful Links</h3>

STL and DXF files are [here.](https://github.com/OpenRacer/OpenRacer/tree/master/cad)<br>
[Join our Facebook group](https://www.facebook.com/groups/640824090407985)<br>
[Buy frame at Five33](https://flyfive33.com/products/five33-open-racer-frame-kit-1?wpam_id=17)<br>
[Freestyle example with GP7](https://www.youtube.com/watch?v=OqChCLXAk6A)<br>
[Racing example with GP7](https://www.youtube.com/watch?v=VN75sF9umTA)<br>
[Racing full speed no gopro](https://www.youtube.com/watch?v=_SSzJq6VKVc)<br>
[DJI racing example](https://www.youtube.com/watch?v=-WxEIBV4bSs)<br>
[Review by Jon E5](https://www.youtube.com/watch?v=laAqQoRC8uU)<br>
[Step-by-step build video by Jon E5](https://youtu.be/wqulm-HaGHg)<br>
<hr>

This design was created from scratch but inspired by the brilliant CampfireQuads frame. Since the Campfire frame isn't open source and pilots wanted to improve the design to add features like support for a Caddx Vista, the OpenRacer frame was created to share with the FPV community. This design has been tested thoroughly by the community, but we're still looking for ways to improve it. Please contribute ideas or submit your own designs through pull requests!

<h3>Recommended carbon thickness</h3>

```
Top and Bottom plates: 2.5mm
Arms: 5mm
Braces: 4mm
```

<h3>Required screws, nuts, and standoffs</h3>

```
- 8x pressnuts M3 (for top plate)
- 4x standoffs 10mm M3 (to mount canopy) rough surface preferably
- M3 plastic nuts X 4 (to secure FC/stack)

Titanium (Grade alloy if titanium not available):
- M3 Button head 12mm X 8 (mount motors through braces and arms)
- M3 Button head 8mm X 4 (mount motors through arms)
- M3 Button head 6mm X 4 (secure canopy from the top)

Alloy Steel (12.9 Gauge Alloy - the best. 10.9 grade also works.
Not aluminium, not titanium, not stainless steel)
- M3 Countersunk 16mm X 4 (arm mounting, goes through both plates, pressnut and standoff)
- M3 Countersunk 30mm X 4 (for 30x30 stack, goes through both plates)

Additional hardware for 20x20 stack builds:
- M3 Countersunk 12.9 Grade Alloy 12mm X 4 (to lock the arms instead of 30x30 stack screws)
- M3 Button head 20mm X 4 (Titanuim or Grade Alloy) (for 20x20 stack)

Extra for 25x25 AIO:
- M2 Button head 12mm X 4
```

All canopies can be printed in 95A shore hardness TPU with the exception of the AnalogPro version. The AnalogPro canopy should be printed in Nylon. A Nylon similar to Taulman 645 is preferred, but for printers with PTFE-lined hotends limited to <250C temperatures, Taulman's lower temp alternatives such as Bridge, 230, or PCTPE are also good choices. If you are unfamiliar with Nylon printing, it has some challenges associated. Drying the filament and keeping it dry is very important, but steps for that will not be covered here.
Taulman recommends 40-60C bed temperature for PCTPE, but some people report that running even lower temperatures (35C) can help avoid warping and adhesion issues. 
Nylon prints should be boiled in water for 5 minutes to restore their flexibility.

![Canopy versions](https://github.com/OpenRacer/OpenRacer/blob/master/img/render_canopies.png?raw=true)


<h3>Suggested print settings for TPU canopies</h3>

```
1.6mm wall thickness (for 0.4mm nozzle, use 0.53mm line width and 3 perimeters to achieve 1.59mm walls. 0.6 to 0.8mm nozzles will use 0.8mm line width and 2 perimeters)
0.2mm layer height recommended, 0.28mm maximum
30-60% fan speed
20% infill (gyroid if available)
Supports are required
Recommended orientation is with standoff legs on the bed. It's possible to print some canopies on the nose to reduce support material, but this can be tricky and has cosmetic disadvantages.
```

<h3>Suggested print settings for Nylon AnalogPro canopies</h3>

```
1.6mm wall thickness (for 0.4mm nozzle, use 0.53mm line width and 3 perimeters to achieve 1.59mm walls. 0.6 to 0.8mm nozzles will use 0.8mm line width and 2 perimeters)
0.2mm layer height recommended, 0.28mm maximum
0% fan speed
20% infill
Supports are required, but only from build plate
Recommended print orientation is with standoff legs on bed. Use care removing supports around the antenna holder. 
```

<h3>Canopy Accessories</h3>

The AnalogPro canopy has a slot on top for an optional fin, which can help when using turtle (flip over after crash) mode. It's recommended to print this part in 95A TPU. If a camera locker is available for a canopy, it will be in the CameraLockers folder for the associated canopy. Camera lockers help maintain your camera angle in crashes and also provide some level of protection.

<p>

AnalogSharpClassic and AnalogSmoothClassic versions work with most of normal 20x20 and 30x30 stacks. 

<p>

![TPU AnalogSharpClassic](https://github.com/OpenRacer/OpenRacer/blob/master/img/photo_AnalogSharpClassic_with_camlocker.jpg?raw=true)
<sub>AnalogSharpClassic with optional GoPro mounts and camera locker.</sub>

<h3>Recommended components for the AnalogPro version</h3>

```
Arms style: Fatty
Canopy Style: PRO - predator nano V5
FC:        Foxeer 20x20 V2
ESC:       Foxeer Reaper 45A or 60A 20x20
Camera:    Foxeer Predator nano V5
VTX:       Rush Tiny Tank
Motors:    Vanover V2 or Headsup
Props:     Dal new Cyclone V2
Batteries: Rline v4 1300Mah 6S or any good brand like Pyroflip, GNB
Antenna:   U.FL TO SMA EXTENSION and small antenna like TrueRc
RX:        Matching RX for your radio. Ghost, Tracer, ELRS, Crossfire, etc.
Other:     Optional short race wires like Pyro race wires, zip ties, double side tape, heatshrink
```

<h3>Recommended components for the Classic versions</h3>

```
FC:        Clracing F7
ESC:       Any 30x30 Blheli32 ESC that is not very big like Spedix, Hobbywing etc. starting from 35A. Be careful, modern 30x30 Aikon and Clracing ESCs are too big. 
Camera:    Runcam Racer 3 or Foxeer Predator Micro V4
VTX:       Rush Tiny Tank
Motors:    RCINPOWER GTS-V2 2207PLUS 2207 1860KV or Vanover Motors or Talon
Props:     Gemfan 51466X3 Hurricane
Batteries: Rline v3 1300Mah 6S or any good brand like Pyroflip, GNB
Antenna:   U.FL TO SMA EXTENSION and small antenna like TrueRc
RX:        Matching RX for your radio. Ghost, Tracer, ELRS, Crossfire, etc.
Other:     Optional short race wires like Pyro race wires, zip ties, double side tape, heatshrink
```
