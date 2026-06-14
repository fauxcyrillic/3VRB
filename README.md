# 3VRB
a little reverb

based on the public domain schematic for "Verbtronic" by Pittsburgh Modular.

---

3x PT2399 chips in series, with a mode toggle to switch between two sets of delay times for each chip for two types of sound.

Rougly speaking, switch left is a more natural, kinda tape delay sort of sound, while switch right is a more metallic, springy sound. (To my ears)

Turn tone left to emphasise low frequencies in the echo, turn right to emphasise high frequencies.

All pots are 100k linear. There's one through-hole resistor used to set the input attenuation into the PT2399. I haven't settled on the perfect value for this yet, hence leaving it t-h to allow testing. Likely the best value is 33k or 47k.

The mode switch is one of these sub-miniature toggles from Thonk: https://www.thonk.co.uk/shop/sub-mini-toggle-switches/
You want SPDT ON-ON so choose DW1 or DWLP1 depending on how tall of a switch you want (DWLP1 is shorter)

They're technically too tall at 8.64mm to fit between panel and PCB in AE (which only allows 8mm). However, they have tiny little plastic 'feet' which you can trim off or file down which makes them *just* fit. They should come with a little washer and nut which i recommend fitting on the panel front to reduce strain on the solder points when flicking the switch (which is very satisfying)


<img width="298" height="1024" alt="3D_PCB3_v2_2026-06-13" src="https://github.com/user-attachments/assets/ebc56bee-6175-4892-a19a-95eda70b009a" />
