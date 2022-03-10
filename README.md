# redox-big-battery
A case for the Redox Wireless keyboard with 18650 capabilities 

This is a custom made version of the [Redox Wireless Keyboard, by mattdibi](https://github.com/mattdibi/redox-keyboard)

With the use of few easy-to-find external components, it will possibile to hook up 2x 18650 batteries and recharge them by simply plugging in a usb cable.

# BOQ (per section)
- 1x Redox Wireless keyboard pcb
- 1x [TP4056](https://www.amazon.it/s?k=tp4056&adgrpid=51421076846&gclid=CjwKCAiA4KaRBhBdEiwAZi1zztkfgKESp_e-iNOL23CPTUs2SWT4-NLGPg1ZLMD9X7JP37CEInR8TRoCaE4QAvD_BwE&hvadid=255148571216&hvdev=c&hvlocphy=1008736&hvnetw=g&hvqmt=e&hvrand=11305013870671949443&hvtargid=kwd-320380134434&hydadcr=25901_1930712&tag=slhyin-21&ref=pd_sl_7x6nzbeh7u_e) or equivalent
- 1x [LM2596](https://www.amazon.it/s?k=lm2596&__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=3C4CGDCJ4NG85&sprefix=lm2596%2Caps%2C81&ref=nb_sb_noss) or equivalent
1x [ON/OFF switch](https://www.amazon.it/HUAYAO-Interruttore-Scorrimento-Verticale-Scorrevole/dp/B08VDX231L/ref=sr_1_22?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=15ZA3OFYWPKF3&keywords=spdt+switch&qid=1646913346&sprefix=spdt+switch%2Caps%2C87&sr=8-22) (if you want to replace the one on board
- 1x [Nickel strip](https://www.amazon.it/Nastro-nickel-lunghezza-saldatrice-batteria/dp/B07CJDK6M4/ref=sr_1_7?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=3W3TEY6HRJKD4&keywords=nickel&qid=1646913233&sprefix=nickel%2Caps%2C109&sr=8-7) for cell contacts
- 16x [6x3 magnets](https://www.amazon.it/Magnetastico-neodimio-frigorifero-permanente-interattiva/dp/B00Z7ZBTLC/ref=sr_1_2?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1EQDFSARIBIW&keywords=magnetastico+6x3&qid=1646912382&sprefix=magnetastico+6+x+3%2Caps%2C141&sr=8-2) (OPTIONAL)
Wires, patience and a soldering iron

# How does it work:
The 18650 battery, which has a nominal voltage of 3.7v, therefore can even reach 4.2v when fully charged, needs to be regulated and limited down by the LM2596 to 3.5-3.6v to not fry the board.
The TP4056 allows to recharge the 18650 via a USB cable, not hindering the normal functioning of the keyboard.

# Extras:
I've decided to also implements slots for 6x3 to allow further expansions of the case without necessarily print it afresh. I've included a version of some tenting that can accomodate magnets.

# Credits:
- [Mattia Dal Ben](https://github.com/mattdibi/redox-keyboard) for the design of this awesome keyboard
- [OlRenso](https://www.thingiverse.com/thing:5237855) for the design of the 18650 minimal holder, which I've customised to fit in this project
- [RappaportDesign](https://www.thingiverse.com/thing:4491679) for the tenting kit, which I've remixed to accomodate a magnet!

![Picture 1](https://user-images.githubusercontent.com/61230589/157656562-6d2f7905-40e8-4081-985d-e2d5eacbf7f8.jpg)
![Picture 2](https://user-images.githubusercontent.com/61230589/157656580-c89a9868-45f7-4947-9c00-b83e650ebca5.jpg)
(Keycaps are custom made in resin)

# TODO:
ASAP I'll upload the wiring.
