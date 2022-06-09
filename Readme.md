# DIY PTH

Some notes on plated-through-hole PCB production in the home lab.

Good YouTubes:

https://www.youtube.com/watch?v=ukfsupePkOM

and

https://www.youtube.com/watch?v=EEmW4xBFiac

## Cleaning:

De-ionised water. Use a water sprayer after tank wash. 

Use a 1.5% NaOH and a drop of dish soap as a pre-cleaner.

## Activation with conductive ink

Liquiwire from either ebay (https://www.ebay.co.uk/itm/223903744472) or from https://liquiwire.tech/products/liquiwire-conductive-ink 

### Method

Paint onto board surface and use a squeegee to push it through all the holes.  Lightly blow on the board to clear the holes. No holes should be left "plugged" with ink.  Put in a warm place, eg on a radiator, or a warm oven for 10 minutes at 80C, then 20 minutes at 120C.

I found small holes (0.4mm) plated perfectly in acid copper at around 10A per square foot (10 mA per sq cm) for around 30 minutes.  Largeer holes (1mm) struggled a little.

## Activation:

Micro-etch with weak Ammonium or Sodium persulphate. Wash then weak stannous chloride solution, wash, then silver nitrate solution.

This should prep the surface of the vias for electroless copper. 
The surface of the vias when activated is reactive and sensitive,  it needs the electroless copper applied as soon as possible.

### Recipe for Stannous Chloride activation solution:

- Tin chloride (Sncl2.2H2O) 30 to 50g/L
- Hydrochloric acid 50 to 100ml/L
- Tin particles 3 to 5g/l

When preparing, first mix water and hydrochloric acid, then add stannous chloride and stir to dissolve. Tin particles can prevent Sn2+ oxidation.

### Good electroless copper recipe:

(by weight)
- 1.33% CuSO4
- 1.8% EDTA  ([CH2N(CH2CO2H)2]2)
Premix the above, can be stored.

When ready to use:
- Add NaOH or KaOH to bring PH to around 13.0

If using NaOH, around 1.5% is about right, but use test strips to confirm.

- Add 10% by volume of 38% formaldehyde. 

Once this stage is done, you have very little time. 
Keep the solution at around room temperature, you have around 30 minutes at most. 
The solution is desperately trying to fall out of solution, it will not store.

