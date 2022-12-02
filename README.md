# DOP (Delivery Of Power) Module

> [WARNING] Please read carefully this note before using this project. It contains important facts.

Content

1. What is **DOP (Delivery Of Power) Module**, and when to use it ?
2. What should you know before using **DOP (Delivery Of Power) Module** ?
3. How to use **DOP (Delivery Of Power) Module** ?
4. Known issues
5. Miscellanous

## 1. What is **DOP (Delivery Of Power) Module**, and when to use it ?

**DOP (Delivery Of Power) Module** is a dc-dc stepdown module based on the XL4005 by XLSEMI.


### Licence

**DOP (Delivery Of Power) Module** is published under the Creative Commons CC0 license. You can find a copy of the licence there : https://creativecommons.org/publicdomain/zero/1.0/legalcode

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**DOP (Delivery Of Power) Module** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

### Release notes

#### v1.0.0

* Schematic, gerbers, bom and cpl files to get CMS assembled.

The 2K variable resistor seems discontinued. At least, it was unavailable at LCSC at time of ordering the first batch.

A selection for the big capacitors, the inductor, and the trimming potentiometer :

|Manufacturer|Mfr. No|Description |
|---|---|---|
|Rubycon|50ZLJ470M12.5X16|Aluminium Electrolytic Capacitors - Radial Leaded LOW IMPEDANCE ELECTROLYTIC CAPACITORS|
|Rubycon|50YXJ470M12.5X20|Aluminium Electrolytic Capacitors - Radial Leaded LOW IMPEDANCE ELECTROLYTIC CAPACITORS|
|KEMET|A759PY687M1HAAE026|Aluminium Organic Polymer Capacitors 50Vol 680uF RAD 2KHr ESR=26 mOhms|
|Coilcraft|VER2923-333KL|Power Inductors - Leaded 33uH Shld 10% 26A 2.6mOhms|
|Coilcraft|AGP2923-333KL|Power Inductors - Leaded 33uH Shld 10% 26A 2.6mOhms AECQ2|
|Bourns|3214W-2-202E|Trimmer Resistors - SMD 4MM SQ MT CERMET TRIMMER SMD|
|Bourns|3214W-1-202G|Trimmer Resistors - SMD 4MM SQ 2KOHMS 10% 5TURN|
|Bourns|3214W-1-202E|Trimmer Resistors - SMD 4mm SQ 2K OHM|



## 2. What should you know before using **DOP (Delivery Of Power) Module** ?

**DOP (Delivery Of Power) Module** is made using Kicad 5.

> Do not use **DOP (Delivery Of Power) Module** if this project is not suitable for your project.

## 3. How to use **DOP (Delivery Of Power) Module** ?

### From sources

To get the latest available work, one must clone the git repository, build and install the package.

	git clone https://github.com/sporniket/dop-module-dc-stepdown-xl4005.git

Then, open the project with Kicad 5.

## 4. Known issues
See the [project issues](https://github.com/sporniket/dop-module-dc-stepdown-xl4005/issues) page.

## 5. Miscellanous

### Report issues
Use the [project issues](https://github.com/sporniket/dop-module-dc-stepdown-xl4005/issues) page.
