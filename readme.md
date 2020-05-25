# UD18 protocol and node-red

This low price device (13.88 EUR) is more than just a digital USB tester. See ATORCH UD18:

- Aliexpress: <https://it.aliexpress.com/item/4000001021645.html>
- Banggood: <https://banggood.app.link/BbTma8WFL6>

![UD18 photo ](images/fig001.jpg)

The measures that UD18 can carry out are:

- Tension: 3.6...32 V
- Current: 0...5.1 A
- Power: 0...163.99 W
- Equivalent resistance: 0...999.99 Ω

Furthermore:

- Time: 0...999 h
- Capacity: 0...99999 mAh (cumulative)
- Charge: 0...999.99 Wh (cumulative)
- USB-data+: 0...2,99 V
- USB-data-: 0...2.99 V

UD18 as also the optional capability to cut off the charge (FCOP) when some trigger conditions are meets.

UD18 can communicate via Bluetooth and two applications can be downloaded, one for Windows PC and another App for smartphone (Android and iPhone).

![The UD18 test flow](images/2020-03-01.161247.shot.png)

To use UD18 in **node-red** custom integrate projects we need:

- the _communication protocol_ used by the device (see [UD18_protocol.txt](UD18_protocol.txt))
- [node-red](https://nodered.org) nodes to _code+send_ commands and _receive+decode_ data (see [UD18flow.json](UD18flow.json)).

For the full story see [UD18_01_en.pdf](UD18_01_en.pdf) (in italiano: [UD18_01_it.pdf](UD18_01_en.pdf)).
