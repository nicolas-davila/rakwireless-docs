---
prev: ../Overview/
next: ../Datasheet/
tags:
    - RAKBox-UO100x75x38
    - Installation Guide
    - WisBlock
    - Enclosure
    - RAK19007
rak_desc: In this guide, the process of assembling and mounting your RAKBox-UO100x75x38 will be shown step by step. Strict adherence to the steps guarantees a secured and durable casing.
rak_img: /assets/images/wisblock/rakbox-uo100x75x38/uo_home.png
---

# Installation Guide

## Package Contents

<br>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/package-content-1.png"
  width="65%"
  caption="Small WisBlock Unify Enclosure package content"
/>


| Number | Name        | Quantity | Material        | Color         |
| ------ | ----------- | -------- | --------------- | ------------- |
| 1      | Top Cover   | 1        | ABS UL94V-0     | White or Grey |
| 2      | Bottom Base | 1        | ABS UL94V-0     | White or Grey |
| 3      | Gasket      | 1        | Silicone        | Black         |
| 4      | Screw       | 4-6      | Stainless steel |               |

## Assembly Guide

### 1. Prepare the Lid and Gasket

First, install the rubber gasket in the groove of the top cover, as shown in **Figure 2**. Put the four corners of the gasket into the groove, and then press the middle gently. Ensure that the gasket is not twisted.

Before assembly, check if the gasket is installed correctly. The rubber gasket helps seal the enclosure properly and protects it from dust and water.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/rubber-gasket.png"
  width="50%"
  caption="Installing the rubber gasket"
/>

### 2. Choose the Internal Mounting Plate

Next is to prepare the mounting plate. There are two types of mounting plates:

- Plain mounting plate
- WisBlock bespoke mounting plate
- WisBlock base plate with antenna

#### Plain Mounting Plate

The plain mounting plate has no holes, except for mounting holes to the enclosure. It is designed to be customized depending on the circuit board to be placed in the enclosure.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/plain-plate.png"
  width="50%"
  caption="Plain mounting plate"
/>

#### WisBlock Bespoke Mounting Plate

The WisBlock Bespoke Mounting Plate is designed specifically to hold WisBlock Base boards. You have to cut the excess bosses or parts with a wire cutter depending on the WisBlock Base board that you have.

The following guide shows what to cut depending on the WisBlock Base board.

::: tip 📝 NOTE
For the cutting reference, the red line is the cut-out area.
:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/cut-out.png"
  width="35%"
  caption="Cutting-out excess parts of the WisBlock Internal mounting plate"
/>

##### RAK5005-O

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/rak5005-o.png"
  width="70%"
  caption="RAK5005-O WisBlock Base board cut-out area"
/>

##### RAK19007

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/rak19007.png"
  width="70%"
  caption="RAK19007 WisBlock Base board cut-out area"
/>

##### RAK19003

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/rak19003.png"
  width="70%"
  caption="RAK19003 WisBlock Base board cut-out area"
/>

#### WisBlock Base Plate with Antenna

The WisBlock Base Plate with Antenna is designed as a special mounting base plate with a built-in antenna for LoRa and BLE. The antennas are optimally designed in terms of RF performance with consideration of the mounted WisBlock Base and other modules. It supports RAK19003 and RAK19007 WisBlock Base boards.

::: tip 📝 NOTE
There are two separate WisBlock Base Plate with Antenna that is optimized for 8xx Mhz and 9xx Mhz band. The 2.4&nbsp;GHz band for BLE is the same for both designs.

- [863-870Mhz Antenna Datasheet](https://downloads.rakwireless.com/LoRa/WisBlock/Accessories/)
- [902-928Mhz Antenna Datasheet](https://downloads.rakwireless.com/LoRa/WisBlock/Accessories/)

:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-plate-antenna.png"
  width="70%"
  caption="WisBlock Base Plate with Built-in Antenna 863-870Mhz (Left) and 902-928Mhz (Right)"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-plate-antenna-dimension.png"
  width="55%"
  caption="WisBlock Base Plate with Built-in Antenna Dimension"
/>

On RAK19007, you have to cut the excess bosses with a sharp wire cutter.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-plate-antenna-cutout.png"
  width="75%"
  caption="Cutting-out excess parts of the WisBlock Internal mounting plate"
/>

### 3. Screw the WisBlock to Internal Mounting Plate

After cutting the Internal Mounting Plate, install the WisBlock Base board onto the Internal Mounting Plate with 2.2*5&nbsp;mm self-tapping screws, as shown in **Figure 11**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/baseboard-plate.png"
  width="50%"
  caption="Installing WisBlock Base board on the internal mounting plate"
/>

There is an extra step on the WisBlock Base plate with a built-in antenna since you have to connect the WisBlock Core's IPEX connector to the IPEX connector of the WisBlock Base plate.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-plate-antenna-wisblock.png"
  width="50%"
  caption="Installing WisBlock Base board on the internal mounting plate with Antenna"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-plate-antenna-connect.png"
  width="50%"
  caption="Connecting the Antenna via IPEX connector"
/>


### 4. Attach the Mounting Plate to the Enclosure

Then, install the WisBlock Internal Mounting Plate to the base of the enclosure using four (4) pieces of M3*4&nbsp;mm Countersunk head screws, as shown in **Figure 14**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/plate-enclosure.png"
  width="50%"
  caption="Installing Internal Mounting Plate to the enclosure"
/>

If you are using the WisBlock Base plate with Antenna, there are very important and critical considerations when attaching it to the Enclosure. To ensure that the LoRa antenna will work on its optimal performance, a keep-out on its area must be implemented.

:::warning ⚠️ WARNING
There should be no metal parts above the red line area in the figure below, such as batteries, solar panels, metal screens, cables, etc. There are no restrictions on the BLE antenna area on the other hand.

In addition, all mounting screws must be fastened well since the metal screws have impact on the performance of the built-in PCB antenna.
:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-antenna-keepout-1.png"
  width="45%"
  caption="LoRa Antenna location on the plate"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wisblock-antenna-keepout-2.png"
  width="50%"
  caption="Keep out illustration"
/>

### 5. Cover the Enclosure with a Lid

Finally, close the WisBlock Unify Enclosure with the top lid using four pieces of M3*8&nbsp;mm head screw with a washer, as shown in **Figure 17**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/close-enclosure.png"
  width="50%"
  caption="Closing the WisBlock Unify Enclosure"
/>

## Mounting Guide

After full assembly of the enclosure, the next step is to choose the right mounting accessory for your application:

- [Pole Mount Vertical (Type A)](#pole-mount-vertical-type-a) <br>
- [Wall Mount (Type D)](#wall-mount-type-d)
- [Belt Clip Mount (Type E)](#belt-clip-mount-type-e)
- [DIN Mount (Type F)](#din-mount-type-f)
- [Magnet Mount (Type G)](#magnet-mount-type-g)
- [Belt Loop Mount (Type H)](#belt-loop-mount-type-h)
- [Label Mount (Type I)](#label-mount-type-i)
- [Hook Loop Mount (Type J)](#hook-loop-mount-type-j)

Each mount accessory has a mark indicated by a capital letter, as shown in **Figure 18**, and each WisBlock Unify Enclosure has several fixed positions, which are indicated by a mark of numerals, as shown in **Figure 19**. The small-sized WisBlock Unify Enclosure has only four (4) fixed positions.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/mount-letter.png"
  width="30%"
  caption="Mount accessories marked with letters"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/enclosure-number.png"
  width="30%"
  caption="WisBlock Unify Enclosure marked with numerals"
/>

### Pole Mount Vertical (Type A)

1. For vertical pole mount, use two (2) pieces of mount accessories, which has an indicated mark of the letter **A**, as shown in **Figure 20**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/pole-vertical-A.png"
  width="40%"
  caption="Mount accessory marked with the letter A"
/>

2. Fix the pole mounts marked with the letter **A** on the WisBlock Unify Enclosure using four (4) pieces of M3*8&nbsp;mm Head screw with a washer. Place it on fixed positions number **1 & 3** of the enclosure as shown in **Figure 21**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/pole-mount-vertical1.png"
  width="40%"
  caption="Fixing the pole mount on the enclosure"
/>

|  Size  | Fix Position |
| :----: | :----------: |
| Small  |    1 & 3     |

3. After fixing the mounts on the enclosure, place the WisBlock Unify Enclosure onto the pole by using two (2) steel strips (60-85&nbsp;mm), as shown in **Figure 22**.

::: tip 📝 NOTE
The steel strips **ONLY** support 60-85&nbsp;mm diameter of the pole.
:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/vertical-pole.png"
  width="20%"
  caption="Fixing the enclosure on the pole"
/>


### Wall Mount (Type D)

1. For wall mount, use two (2) pieces of mount accessories with an indicator marked with the letter **D**, as shown in **Figure 23**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wall-mount-D.png"
  width="40%"
  caption="Mount accessory marked with the letter D"
/>

2. Fix the wall mounts marked with the letter **D** on the WisBlock Unify Enclosure using four (4) pieces of M3*8&nbsp;mm head screw with a washer. Place it on fixed positions number **1 & 3** or **2 & 4** of the enclosure, as shown in **Figure 24**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wall-mount1.png"
  width="40%"
  caption="Fixing the wall mount on the enclosure"
/>

| Size  | Fix Position   |
| :---: | :------------: |
| Small | 1 & 3 or 2 & 4 |

3. Lastly, follow the steps below, as also shown in **Figure 25**:

- **Step 1**: Use a Φ5&nbsp;mm drill head to drill holes in the wall. Drill at least 55-60&nbsp;mm in depth.
- **Step 2**: Plug the screw anchors into the drilled holes. You can use a hammer to plug it in. It helps the screws to have a secure fit on the wall.
- **Step 3**: Fix the WisBlock Unify Enclosure on the wall using two (2) pieces of ST3.5*35&nbsp;mm tapping screws.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/wall-enclosure.png"
  width="40%"
  caption="Fixing the enclosure on the wall"
/>


### Belt Clip Mount (Type E)

1. For belt clip mount, use one (1) piece of mount accessory with an indicator marked with the letter **E**, as shown in **Figure 26**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-clip-E.png"
  width="30%"
  caption="Mount accessory marked with the letter E"
/>

2. Fix the belt clip mount marked with the letter **E** on the WisBlock Unify Enclosure using two (2) pieces of M3*8&nbsp;mm Head screw with washer. Place it on fixed positions number **1 or 3** of the enclosure as shown in **Figure 27**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-clip1.png"
  width="40%"
  caption="Fixing the belt clip mount on the enclosure"
/>

| Size  | Fix Position |
| :---: | :----------: |
| Small |    1 or 3    |

3. Lastly, clip the unify enclosure on the belt directly as shown in **Figure 28**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-clip-enclosure.png"
  width="30%"
  caption="Fixing the enclosure on the belt clip"
/>

### DIN Mount (Type F)

1. For DIN mount, use two (2) pieces of mount accessories with an indicator marked with the letter **F**, as shown in **Figure 29**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/din-mount-F.png"
  width="50%"
  caption="Mount accessory marked with the letter F"
/>

2. Fix the DIN mount marked with the letter **F** on the WisBlock Unify Enclosure using four (4) pieces of M3*8&nbsp;mm Head screw with the washer. Place it on fixed positions number **1 & 3** or **2 & 4** of the enclosure as shown in **Figure 30** and **Figure 31**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/din-mount1.png"
  width="40%"
  caption="Fixing the DIN mount on the enclosure's position number 1 & 3"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/din-mount2.png"
  width="40%"
  caption="Fixing the DIN mount on the enclosure's position number 2 & 4"
/>

| Size  | Fix Position         |
| :---: | :------------------: |
| Small |    1 & 3 or 2 & 4    |

3. Lastly, clamp the buckle of the DIN mount kit at one end on the edge of the DIN rail, then rotate and press the enclosure to clamp the other end as shown in **Figure 32**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/din-mount-enclosure.png"
  width="50%"
  caption="Fixing the enclosure on the DIN rail"
/>

### Magnet Mount (Type G)

1. For magnet mount, use one (1) up to two (2) pieces of mount accessories with an indicator marked with the letter **G** as shown in **Figure 33**.

::: tip 📝 NOTE
- The number of magnets to be used will depend on the weight of the device and enclosure.
:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/magnet-mount-G.png"
  width="30%"
  caption="Mount accessory marked with the letter G"
/>

2. Fix the magnet mount marked with the letter **G** on the WisBlock Unify Enclosure using one (1) to two (2) pieces of M3*8&nbsp;mm Head screw with washer. Place it on fixed positions number **1 & 3** of the enclosure as shown in **Figure 34**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/magnet-mount1.png"
  width="40%"
  caption="Fixing the magnet mount on the enclosure"
/>

| Size  | Fix Position   |
| :---: | :------------: |
| Small |    1 & 3       |

3. Place the magnets onto the mounting as shown in **Figure 35**.

::: tip 📝 NOTE
- Confirm the number of magnets according to the weight of the device. The small unify enclosure supports up to 2 magnets.
:::

:::warning ⚠️ WARNING
- Avoid placing the enclosure too high or in an environment that vibrates, shocks, or is unstable because doing so could result in equipment damage or physical injury.
- The effect of magnet adsorption is related to the material of adsorption position, surface spraying thickness, and roughness, so it can only be used after confirming that the installation effect is not a problem. If the surface condition of the installation position is not good, it may also affect the reliability of the magnet installation.
- When the enclosure is fixed on the desk by magnetic suction, do not push it back and forth artificially, otherwise, the coating on the contact surface will be damaged.
- During installation, pay attention to the fixation of the external cable of the device to avoid falling off the enclosure due to the excessive weight of the external cable, resulting in personal injury or equipment damage.
- Do not put the magnet close to the magnetic card and other products, or else the stored content of the product may be erased.
- Do not put the magnet close to the computer and other electronic equipment susceptible to the magnetic field, otherwise, it may cause electronic equipment-related failure.
:::

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/magnet-mount2.png"
  width="40%"
  caption="Fixing the magnet mount on the enclosure"
/>

- The magnet should be ordered separately. Consult before placing an order.

|  No.  |  Diameter  | Thickness | Material |    Adsorption    |
| :---: | :--------: | :-------: | :------: | :--------------: |
|   1   | 20&nbsp;mm | 3&nbsp;mm |  NdFeB   | 2800 Gauss (TBD) |
|   2   | 20&nbsp;mm | 5&nbsp;mm |  NdFeB   | 3100 Gauss (TBD) |


:::warning ⚠️ WARNING
Handle with care to avoid personal injury or damage to the magnet.
:::


4. Lastly, attach the unify enclosure to a metallic surface. Be careful not to pinch your fingers due to the high magnetism.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/magnet-mount-enclosure.png"
  width="40%"
  caption="Fixing the enclosure onto the metal surface"
/>


### Belt Loop Mount (Type H)

1. For belt loop mount, use two (2) pieces of mount accessories with an indicator marked with the letter **H**, as shown in **Figure 37**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-loop-H.png"
  width="40%"
  caption="Mount accessory marked with the letter H"
/>

2. Fix the belt loop mount marked with the letter **H** on the WisBlock Unify Enclosure using four (4) pieces of M3*8&nbsp;mm Head screw with a washer. Place it on fixed positions number **1 to 4** of the enclosure as shown in **Figure 38**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-loop1.png"
  width="40%"
  caption="Fixing the belt loop mount on the enclosure"
/>

| Size  | Fix Position |
| :---: | :----------: |
| Small |    1 - 4     |

3. Lastly, thread the belt through the hole of the unify enclosure as shown in **Figure 39**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/belt-loop-enclosure.png"
  width="50%"
  caption="Fixing the enclosure on the belt thread"
/>


### Label Mount (Type I)

1. For label mount, use one (1) piece of mount accessory with an indicator marked with the letter **I**, as shown in **Figure 40**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/label-mount-I.png"
  width="30%"
  caption="Mount accessory marked with the letter I"
/>

2. Fix the label mount marked with the letter **I** on the WisBlock Unify Enclosure using two (2) pieces of M3*8&nbsp;mm Head screw with washer. Place it on fixed position numbers **1 to 4** of the enclosure as shown in **Figure 41**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/label-mount1.png"
  width="40%"
  caption="Fixing the label mount on the enclosure"
/>

| Size  | Fix Position |
| :---: | :----------: |
| Small |    1 - 4     |

3. Lastly, you can paste a 30 x 18&nbsp;mm Fillet R4 label in the label zone as shown in **Figure 42** and **Figure 43**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/label-size.png"
  width="50%"
  caption="Label dimension"
/>

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/label-mount-enclosure.png"
  width="25%"
  caption="Attaching the label on the enclosure"
/>


### Hook Loop Mount (Type J)

1. For hook loop mount, use one (1) piece of mount accessory with an indicator marked with the letter **J**, as shown in **Figure 44**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/hook-loop-J.png"
  width="30%"
  caption="Mount accessory marked with the letter J"
/>

2. Fix the hook loop mount marked with the letter **J** on the WisBlock Unify Enclosure using two (2) pieces of M3*8&nbsp;mm Head screw with washer. Place it on fixed position number **1 or 3** of the enclosure as shown in **Figure 45**.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/hook-loop1.png"
  width="40%"
  caption="Fixing the hook loop mount on the enclosure"
/>

| Size  | Fix Position |
| :---: | :----------: |
| Small |    1 or 3    |

3. Lastly, hang the unify enclosure directly on a hook.

<rk-img
  src="/assets/images/wisblock/rakbox-uo100x75x38/installation/hook-loop-enclosure.png"
  width="20%"
  caption="Fixing the enclosure on the hook"
/>
