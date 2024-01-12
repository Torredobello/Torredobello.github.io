---
layout: page
title: Wind System Assessment
bigimg:
  - "/img/big-img/windturbine.jpg"
  - "/img/big-img/windmill.jpg"
---

A WTS produces power 𝑃𝑤𝑇 when the wind speed V is higher than the cut-in speed Vci and is shut-down when V is higher than the cut-out speed Vco. When:
- *Vr≤V ≤ Vco(Vr is the rated wind speed)*, the WTG produces rated power 𝑃𝑟.
- If *Vci≤V ≤ Vr*, the WTS output power varies according to the cube law.

The following equations are to be used to model the WTS [4, 5]:
- *𝑃𝑤𝑇={ **𝑃𝑟×(𝑉^3−𝑉𝑐𝑖^3/𝑉𝑟^3−𝑉𝑐𝑖^3)**,Vci≤V ≤ Vr | **𝑃𝑟**, Vr≤V ≤ Vco | **0** , Vco≤V or V≤ Vci}*    (1)
Where:
- *𝑃𝑟= 12×𝐶𝑝×𝜌𝑎𝑖𝑟× 𝐴𝑊𝑇×𝑉𝑟^3*    (2)
  
In the above equation, 𝐶𝑝, 𝜌𝑎𝑖𝑟, and 𝐴𝑊𝑇 are the power coefficient, air density, and rotor swept area, respectively. To calculate the wind speed, 𝑉, at the desired WTS installation height, 𝐻, which is usually different from the height corresponding to the wind speed input data, the exponential law is used: 𝑉= 𝑉𝑟𝑒𝑓×(𝐻𝑎𝐻𝑟𝑒𝑓 𝑎) (9)
where 𝑉𝑟𝑒𝑓 is the reference (input) wind speed (m/s) measured at height 𝐻𝑟𝑒𝑓 (m) and 𝑎 is the power law exponent, ranging from 1/7 to 1/4 and approximately chosen as 1/7 for open land.
<iframe width="560" height="315" src="https://www.youtube.com/embed/xy9nj94xvKA?si=nF1Rsb-6S_440-cp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
