
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

The Ender 2 Pro runs on 12 volts, where as many LED strips run on 12V. If using 12V leds, add a 12V buck converter or DC-DC Converter. 
[This one](https://www.amazon.com/gp/product/B0758ZTS61/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) should be fine for up to 1Amp of current (Add a heatsync if planning on using more than 1Amp). 

You will need to splice in power from the 24V output of the circuit board. For safety, it is reccomended to _NOT_ add tinned wire to the wires that will be
crimped in the screw terminal. The best connection will be with a [Ferrule Crimping Tool](https://www.amazon.com/dp/B07WRQN45C/ref=cm_sw_em_r_mt_dp_77HQ230C1YMWYS03GKH8).



## :globe_with_meridians: Links



- **Github**: [https://github.com/spuder/ender2pro-led-bracket](https://github.com/spuder/ender2pro-led-bracket)

## :triangular_ruler: CAD files

3d files are located in the [CAD](./CAD) directory.
- `*.f3d` = Fusion 360 Files
- `*.stl` = 3d Printable Files

| Filename | STL | GIF | 
| --- | --- | --- | 
| [CAD/EndCap Open.stl](./CAD%2FEndCap%20Open.stl) | ![](./CAD%2FEndCap%20Open.stl.png) | ![](./CAD%2FEndCap%20Open.stl.gif) | 
| [CAD/EndCap Closed.stl](./CAD%2FEndCap%20Closed.stl) | ![](./CAD%2FEndCap%20Closed.stl.png) | ![](./CAD%2FEndCap%20Closed.stl.gif) | 
| [CAD/M3 LED Bracket.stl](./CAD%2FM3%20LED%20Bracket.stl) | ![](./CAD%2FM3%20LED%20Bracket.stl.png) | ![](./CAD%2FM3%20LED%20Bracket.stl.gif) | 
| [CAD/M4 LED Bracket.stl](./CAD%2FM4%20LED%20Bracket.stl) | ![](./CAD%2FM4%20LED%20Bracket.stl.png) | ![](./CAD%2FM4%20LED%20Bracket.stl.gif) | 

## :notebook: Resources

- [LED Diffuser](https://www.amazon.com/Muzata-Aluminum-Mounting-Installations-Diffuser/dp/B01M09PBYX/ref=pd_lpo_3?pd_rd_i=B01M09PBYX&psc=1)


- [JST Connector](https://www.amazon.com/eBoot-Connector-Female-Cable-Battery/dp/B01M5AHF0Z/ref=sr_1_2?crid=Y3ZXLKZ6CAED&keywords=jst+connector&qid=1640284019&sprefix=jst+co%2Caps%2C473&sr=8-2)


- [12 V Buck Converter](https://www.amazon.com/gp/product/B0758ZTS61/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)


- [Ender 2 Pro](https://www.creality3dofficial.com/products/creality-ender-2-3d-printer)


- [T-Nuts](https://www.thingiverse.com/thing:3050607/files)


- [Ferrule Crimping Tool](https://www.amazon.com/dp/B07WRQN45C/ref=cm_sw_em_r_mt_dp_77HQ230C1YMWYS03GKH8)


## :camera: Photos


![](photos%2FIMG_1110.jpeg)



![](photos%2FIMG_0934.jpeg)



![](photos%2FIMG_1001.jpeg)



![](photos%2FIMG_0990%202.jpeg)



![](photos%2FScreen%20Shot%202021-12-25%20at%2010.21.51%20AM.png)



![](photos%2FIMG_1109.jpeg)


---

## MIT License ![](https://img.shields.io/badge/license-MIT-lightgrey) 
[(what does this mean?)](https://choosealicense.com/licenses/mit/)



---
## Template
The contents of this readme were automatically generated from this [:notebook: template](https://github.com/spuder/CAD-template). 

Use this template yourself by clicking here: 

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/ntkme/github-buttons/generate" data-color-scheme="no-preference: dark; light: light; dark: dark;" data-icon="octicon-repo-template" data-size="large" aria-label="Use this template ntkme/github-buttons on GitHub">Use this template</a>


```
make all
# or
make clean; make stl; make jpeg; make template
```