<a id="other-tips-and-handles"></a>
# Tips and Handles

<!-- MarkdownTOC -->

* [T12 Thermocouple](#t12-thermocouple)
* [T245 / C245](#t245--c245)
	* [Hazar Blog](#hazar-blog)
* [Universal Soldering Iron - Various](#universal-soldering-iron---various)
		* [HAKKO T12](#hakko-t12)
		* [HAKKO FX8801, HAKKO 907 \(original, with PTC sensor\)](#hakko-fx8801-hakko-907-original-with-ptc-sensor)
		* [JBC C245](#jbc-c245)
		* [JBC C210](#jbc-c210)
		* [JBC Microtweezers](#jbc-microtweezers)
		* [WELLER WSP80](#weller-wsp80)
		* [ERSA RT80](#ersa-rt80)

<!-- /MarkdownTOC -->


<a id="t12-thermocouple"></a>
## T12 Thermocouple

The T12 thermocouple is oddball metallurgy, measured empirically in Hakko Patent US6087631A for the look up table, 20-21uV/°C accurate from 200°-600°C.

* Specifically we try to gather information on JBC tips (aka 'cartridges').


<a id="t245--c245"></a>
## T245 / C245

<a id="hazar-blog"></a>
### Hazar Blog

Hazar's investigations into C245 thermocouple, using the MAX6675
* Original version: [on Hazar's Blog](http://www.hazarkarabay.com.tr/elektronik/jbc-kontrolcu-sicaklik-olcumu/)
* **Accessible version:** [Mirrored, translated to english](https://htmlpreview.github.io/?https://github.com/dreamcat4/t12-t245-controllers-docs/blob/master/tips-and-handles/t245-c245/JBC%20Controler_%20Temperature%20Measurement%20(2020-06-16%2010_25_36).html)


<a id="universal-soldering-iron---various"></a>
## Universal Soldering Iron - Various

* **Taken from:** The "Really Universal Soldering Controller" project.
* **Source:** [http://dangerousprototypes.com/forum/index.php?topic=7218.0#p66362](http://dangerousprototypes.com/forum/index.php?topic=7218.0#p66362)


<a id="hakko-t12"></a>
#### HAKKO T12

- Outer shell, and heater negative (middle) terminal connected together to Vout1- and EARTH
- heater positive (bottom terminal) connected to Vout1+ and SENSEA
- 1k resistor between ID and Vout1-
- 5.6k resistor between ID and Vout2-

<a id="hakko-fx8801-hakko-907-original-with-ptc-sensor"></a>
#### HAKKO FX8801, HAKKO 907 (original, with PTC sensor)

- Outer shell, PTC negative and heater negative connected to EARTH, Vout1- and SENSEB
- Heater positive connected to Vout1+
- PTC positive connected to SENSEA
- 1k between ID and Vout1-
- 820ohm between ID and Vout2-

<a id="jbc-c245"></a>
#### JBC C245

- Outer shell (green wire) connected to EARTH and SENSEB
- Heater positive(red wire) connected to Vout1- and SENSEA
- Heater negative(blue wire) connected to Vout1+
- 150ohm between ID and Vout1-
- 5.6k between ID and Vout2-

<a id="jbc-c210"></a>
#### JBC C210

- Outer shell (green wire) connected to EARTH and SENSEB
- Heater negative (middle terminal, blue wire) connected to Vout1-
- Heater positive (smaller terminal, red wire) connected to Vout1+ and SENSEA
- 3.0k between ID and Vout1-
- 5.6k between ID and Vout2-

<a id="jbc-microtweezers"></a>
#### JBC Microtweezers

- Outer shell of both tips (green wire) connected to EARTH
- Heater 1 negative (blue wire) connected to Vout1-
- Heater 1 positive (red wire) connected to Vout1+ and SENSEA
- Heater 2 negative (brown wire) connected to Vout2-
- Heater 2 positive (yellow wire) connected to Vout2+ and SENSEB
- 1.0k between ID and Vout1-

<a id="weller-wsp80"></a>
#### WELLER WSP80

- Outer shell, PTC negative and heater negative (white, black and brown wires) connected to EARTH, Vout1- and SENSEB
- Heater positive (blue wire) connected to Vout1+
- PTC positive (red wire) connected to SENSEA
- 120ohm between ID and Vout1-
- 5.6k between ID and Vout2-

<a id="ersa-rt80"></a>
#### ERSA RT80

- Outer shell and Heater/PTC negative (pink and white wires) connected to EARTH, Vout1- and SENSEB
- Heater/PTC positive (black wire) connected to Vout1+ and SENSEA
- 300ohm between ID and Vout1-
- 110ohm between ID and Vout2-


