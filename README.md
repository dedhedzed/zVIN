# zVIN
**Decode VINs (Vehicle Identification Numbers) using a Flipper Zero - HUUUUUUUUGE WIP**

![zvin](https://github.com/dedhedzed/zVIN/assets/106502744/94fa7b2d-da4d-43ae-ad56-403c133bad80)

:canada: By [Zachary Zed (DedHedZed) :canada:](https://github.com/dedhedzed/ "well in theory it's Zachariah Zed the Third, His Supreme Excellency, but I go by Zed.")
-----
**:skull_and_crossbones: *greetz 2 tha mateys* :skull_and_crossbones:**

**:skull_and_crossbones: [RG](https://github.com/RocketGod-git "the one and only muffugin rocketgod" ) :skull_and_crossbones:**

**:skull_and_crossbones: [Skel](https://github.com/SkeletonMan03 "skeletanarchy mafuckaaaaz" ) :skull_and_crossbones:**

**:skull_and_crossbones: [Bill](https://github.com/billNYEusesMYwifi "inertia is a property of matter ;)" ) :skull_and_crossbones:**

**:skull_and_crossbones: [Jimi](https://github.com/jimilinuxguy "shanita d ;)" ) :skull_and_crossbones:**

**:skull_and_crossbones: [FP](https://github.com/FalsePhilosopher "i don't chase hoes, hoes chase me" ) :skull_and_crossbones:**

**:skull_and_crossbones: [p00ter](https://github.com/sierra-tang0 "microwave it" ) :skull_and_crossbones:**

**:skull_and_crossbones: Kraken (*bagged milk?!*) :skull_and_crossbones:**

**:skull_and_crossbones: and the many i may have forgotten... :skull_and_crossbones:**

**:metal: ***much love, long live APT69420*** :metal:**
### :fu: I FORBID ROGUEMASTER FROM INCLUDING THIS WITHOUT PROPER CREDIT!!! I NEVER GAVE PERMISSION AND NEVER WILL GIVE PERMISSION TO ROGUEMASTER TO USE MY CODE IN ANY WAY, SHAPE OR FORM WITHOUT PROPER CREDIT!!! SEE credits.md FOR A FULL LIST OF CREDITS!!! :fu:

## 🚗 ❓ What is a VIN? ❓ 🚗

A VIN, or *Vehicle Identification Number*, is a (since 1981) 17-digit number required on **every** vehicle sold ***ever***. [A typical](https://www.iso.org/standard/52200.html "ISO 3779") VIN will fall under this structure:

![vin-chart](https://github.com/dedhedzed/zVIN/assets/106502744/9e34fe8b-60e9-498a-ad83-b30f13b11dec)

The **3rd digit** will ***always*** be a **9** if the manufacturer makes/sells ***less*** than a certain amount of vehicles. In the EU, this is **500 vehicles.** In North America, we're looking at **2,000 vehicles**.

The **9th digit** is ***always*** a check digit on vehicles sold in the United States and Canada; on vehicles sold elsewhere, it will fall under the **vehicle attributes**. 

The **10th and 11th digits** give information as to what model year and plant the vehicle has been assembled in only for **North American VINs**. In Europe, it would be a part of [***the clear identification of a particular vehicle***](https://en.wikipedia.org/wiki/Vehicle_identification_number#Components) section ~~fuckin~~ thing.

Unless the number of produced vehicles is ***under 2000 units a year***, digits **12 to 17** are **ALWAYS** a ***sequential number***, aka what number it has on the production line. For example, if your sequential number is **002161**, your car is the **2161st** one to have rolled off the assembly line. In cases where the manufacturer produces **less** or **exactly** 2 thousand units, digits **12 to 14** are a ***manufacturer identifier***.

## ❓ 🧠 Why make this? :brain: ❓

Well, ~~fuck you, that's why~~ the Flipper Zero happens to be a ***pretty decently sized and capable*** device that **MANY** mafuckas have as a part of their EDC (me included). Something this small and discreet can easily be used to stealthily or conveniently, depending on the assignment/use, **decode and save decoded VIN numbers**, amongst other things. Since decoding a VIN isn't necessarily *too* hard, but most services out there are **online only** or **require a smart phone** to use. Having something local and **guaranteed** not to log anything (unless you ***choose to save a decoded VIN!***) is an interesting take on the whole VIN decoding thing.

## 📖 👀 Sources + Additional Goodies :eyes: :book:

- [*Wikipedia article on VINs*](https://en.wikipedia.org/wiki/Vehicle_identification_number)
- [*WikiBooks page with more info*](https://en.wikibooks.org/wiki/Vehicle_Identification_Numbers_(VIN_codes))
- [*NHTSA's VIN Decoder (API available!)*](https://vpic.nhtsa.dot.gov/decoder/)

## ✔️ 🛠️ Planned Features 🛠️ ✔️
- VIN Decoding with support for Partial VINs;
- Decode from File or User Input;
- Save Decoded VINs to a text file;
- Support for exotic/sub-threshold manufacturers.
