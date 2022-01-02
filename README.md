
# Ender-2 Pro LED Bracket
Braket to hold a LED bar on the Creality Ender 2 pro

## Versions
This comes in a M3 or M4 Bolt version. (M3 Pictured)


## Parts / Assembly
- M3 x 12mm Nuts (4)
- M3 x 12mm Screws (4)
- 4 T-Nuts (I printeed these [M3 TNUT](https://www.thingiverse.com/thing:3050607/files) holders)
- 10 - 12 inches of [LED Diffuser](https://www.amazon.com/Muzata-Aluminum-Mounting-Installations-Diffuser/dp/B01M09PBYX/ref=pd_lpo_3?pd_rd_i=B01M09PBYX&psc=1)
- Wire
- 24 / 12 V LEDs
- 12V Buck converter (optional)

The Ender 2 Pro runs on 24 volts, whereas many LED strips run on 12V. If using 12V leds, add a 24-12V buck converter or DC-DC Converter. 
[This one](https://www.amazon.com/gp/product/B0758ZTS61/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) should be fine for up to 1Amp of current (Add a heatsync if planning on using more than 1Amp). 

You will need to splice in power from the 24V output of the circuit board. For safety, it is reccomended to _NOT_ add tinned wire to the wires that will be
crimped in the screw terminal. The best connection will be with a [Ferrule Crimping Tool](https://www.amazon.com/dp/B07WRQN45C/ref=cm_sw_em_r_mt_dp_77HQ230C1YMWYS03GKH8).



## :globe_with_meridians: Links



- **Thingiverse**: [https://www.thingiverse.com/thing:5176620](https://www.thingiverse.com/thing:5176620)
- **Github**: [https://github.com/spuder/ender2pro-led-bracket](https://github.com/spuder/ender2pro-led-bracket)

## :triangular_ruler: CAD files

3d files are located in the [CAD](./CAD) directory.
- `*.f3d` = Fusion 360 Files
- `*.stl` = 3d Printable Files

| Filename | STL | GIF | 
| --- | --- | --- | 
| [CAD/EndCap Open.stl](./CAD%2FEndCap%20Open.stl) | ![](./CAD%2FEndCap%20Open.png) | ![](./CAD%2FEndCap%20Open.gif) | 
| [CAD/EndCap Closed.stl](./CAD%2FEndCap%20Closed.stl) | ![](./CAD%2FEndCap%20Closed.png) | ![](./CAD%2FEndCap%20Closed.gif) | 
| [CAD/M3 LED Bracket.stl](./CAD%2FM3%20LED%20Bracket.stl) | ![](./CAD%2FM3%20LED%20Bracket.png) | ![](./CAD%2FM3%20LED%20Bracket.gif) | 
| [CAD/M4 LED Bracket.stl](./CAD%2FM4%20LED%20Bracket.stl) | ![](./CAD%2FM4%20LED%20Bracket.png) | ![](./CAD%2FM4%20LED%20Bracket.gif) | 

## :notebook: Resources
- [LED Diffuser](https://www.amazon.com/Muzata-Aluminum-Mounting-Installations-Diffuser/dp/B01M09PBYX/ref=pd_lpo_3?pd_rd_i=B01M09PBYX&psc=1)
- [JST Connector](https://www.amazon.com/eBoot-Connector-Female-Cable-Battery/dp/B01M5AHF0Z/ref=sr_1_2?crid=Y3ZXLKZ6CAED&keywords=jst+connector&qid=1640284019&sprefix=jst+co%2Caps%2C473&sr=8-2)
- [12 V Buck Converter](https://www.amazon.com/gp/product/B0758ZTS61/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
- [Ender 2 Pro](https://www.creality3dofficial.com/products/creality-ender-2-3d-printer)
- [T-Nuts](https://www.thingiverse.com/thing:3050607/files)
- [Ferrule Crimping Tool](https://www.amazon.com/dp/B07WRQN45C/ref=cm_sw_em_r_mt_dp_77HQ230C1YMWYS03GKH8)

## :camera: Photos
![](photos%2FIMG_1110.jpeg)
![](photos%2FRender1.png)
![](photos%2FIMG_0934.jpeg)
![](photos%2Fcropped)
![](photos%2FIMG_1001.jpeg)
![](photos%2FIMG_0990%202.jpeg)
![](photos%2FScreen%20Shot%202021-12-25%20at%2010.21.51%20AM.png)
![](photos%2FIMG_1109.jpeg)
---

## Creative Commons License 
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


---
## Template
The contents of this readme were automatically generated from this [:notebook: template](https://github.com/spuder/CAD-template). <a class="github-button" href="https://github.com/spuder/CAD-template/generate" data-color-scheme="no-preference: dark; light: light; dark: dark;" data-icon="octicon-repo-template" data-size="large" aria-label="Use this template spuder/CAD-template on GitHub">Click here to use this template</a>



```
make all
# or
make clean; make stl; make jpeg; make template
```