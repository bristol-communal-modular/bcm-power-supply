# Parts

Most of the components should be relatively easy to find (resistors, LEDs and capacitors for example) but a couple need to be specific.
This doc has links to the parts on a few websites, and some information about them that's worth bearing in mind when finding alternatives. NOTE: We've only sourced from Mouser, not from the other sites, but the parts *should* be the same.

## Regulators

N78 series regulators are used. The footprints on the PCB are designed for the enclosed version with a bend in the output pins so they sit flat on the board. The upright versions will work fine but will make the finished version taller which may be an issue depending on how much space there is in the case.

These parts are all the 2 Amp versions. There are apparently 1 Amp versions available which will probably be cheaper, but it doesn't seem possible to find them in the version that lies flat.

### 12V

N7812-2CH

[Mouser - 709-N7812-2CH](https://www.mouser.co.uk/ProductDetail/MEAN-WELL/N7812-2CH?qs=IKkN%2F947nfBns4sWKJt8PA%3D%3D)
[DigiKey - 1866-N7812-2CH-ND](https://www.digikey.com/en/products/detail/mean-well-usa-inc/N7812-2CH/24762172)
[Farnell - 4573217](https://uk.farnell.com/mean-well/n7812-2ch/dc-dc-converter-non-isolated-2a/dp/4573217)

### 5V

N7805-2CH

[Mouser - 709-N7805-2CH](https://www.mouser.co.uk/ProductDetail/MEAN-WELL/N7805-2CH?qs=IKkN%2F947nfA18hHQO%252BQQew%3D%3D)
[DigiKey - 1866-N7805-2CH-ND](https://www.digikey.com/en/products/detail/mean-well-usa-inc/N7805-2CH/24762182)
[Farnell - 4573207](https://uk.farnell.com/mean-well/n7805-2ch/dc-dc-converter-non-isolated-2a/dp/4573207)

## Inductors

The SN3-200 is specified for here, which is 10uH. It's chosen based on the values in the datasheet for the regulators, but it's worth noting it only has a maximum current of 1 Amp. There are larger inductors available, but the pitch on the footprint holes is only 5mm so some of them may not fit.
Will likely end up redesigning this with a different part, but it's fine for now.

SN3-200

[Mouser - 80-SN3-200](https://www.mouser.co.uk/ProductDetail/80-SN3-200)
[DigiKey - 399-20545-ND](https://www.digikey.com/en/products/detail/kemet/SN3-200/9955561?s=N4IgTCBcDaIM4DsDMBaMAGdIC6BfIA)
[Farnell - 2949420](https://uk.farnell.com/kemet/sn3-200/common-mode-choke-10uh-1a/dp/2949420)

## Fuse Holder

05200101Z by Littelfuse Inc.

None of the images on the websites is correct. There are just the metal parts without the plastic surround, and so two of them are needed, one for each end.

[Mouser - 576-05200101Z](https://www.mouser.co.uk/ProductDetail/576-05200101Z)
[DigiKey - F1504-ND](https://www.digikey.com/en/products/detail/littelfuse-inc/05200101Z/554336)
[Farnell - 1608232](https://uk.farnell.com/littelfuse/05200101z/fuseholder-2x20mm/dp/1608232)

## Terminal blocks

The build uses the version from Phoenix Contact, which is a well known brand. There may be other, cheaper alternatives though.
Also you could go without these and just solder wires directly from the DC Jack to the PCB if you want.

[Mouser - 651-1715022](https://www.mouser.co.uk/ProductDetail/651-1715022)
[DigiKey - 277-1258-ND](https://www.digikey.com/en/products/detail/phoenix-contact/1715022/260626)
[Farnell - 3714240](https://uk.farnell.com/phoenix-contact/mkds-1-5-2/terminal-block-wire-to-brd-2pos/dp/3714240)
