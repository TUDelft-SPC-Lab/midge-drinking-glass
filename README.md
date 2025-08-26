# Smart Drinking Cups
This is the public repository for the Smart Drinking Cups open hardware. 

## Project Overview
### Rationale
The cup provides a practical way to embed sensing technology into a familiar everyday object, allowing researchers to study human behavior in naturalistic social settings. By holding the SPCL Midge Badge in a consistent and unobtrusive position, the design ensures reliable data capture of formats like audio, proximity and motion data, while maintaining the normal function of a drinking vessel. Such an approach can be replicated in other contexts where seamless integration of sensors into daily activities is needed. The design allows for future adaptability to different vessel types and sensing functions, making it a flexible tool for social and behavioral research.


### Hardware
The following components are needed to assemble a cup:
- [Zara home glasses](https://www.zarahome.com/nl/recht-kristallook-drinkglas-l40254402?ct=true&categoryId=1020261540&colorId=990)
- [Transparent silicon sleeves](https://www.amazon.nl/dp/B0BVFHP79J?ref=ppx_yo2ov_dt_b_fed_asin_title)
- A transparent cradle(this was 3d printed by us, with xxxx filament. The relevant .exif file is in the repository named xxxx)
- [a Midge](https://github.com/TUDelft-SPC-Lab/spcl_midge_hardware)
- Some double sided tape(optional)

The software required for the initialization of the midge and its software can be found both in its [hardware](https://github.com/TUDelft-SPC-Lab/spcl_midge_hardware) and [software](https://github.com/TUDelft-SPC-Lab/midge-code) repositories. 

### Assembly/ Getting Started
1. The Cup can be assembled by first turning the midge on and placing it in the cradle then attaching double sided tape to it. 
2. Ensure that the midge is resting on the extruding bit of plastic at the bottom of the cradle
3. Then the glass should be placed above the cradle, and you should push the midge upwards from the opposite hole of the cradle, so that the tape sticks to the bottom of the glass
4. Then the whole thing should be pressed into the sleeves tightly. 
5. Ensure that the cradle and glass are straight and coincide with one another


## Operation

During assembly the midge should have been left on. In this case following the instructions of the midge initialization, you can connect to the midge via the code in [this](https://github.com/TUDelft-SPC-Lab/midge-code) repository. After connecting to the midge via the interface of your choice, you can turn on the microphone/IMU/Bluetooth sensor data and the midge will begin recording, so you can use the glass as you wish. 

When the experiment is done, any liquid in the glass should be removed, and the glass should be taken out of the sleeve. After this the Midge can safely be extracted from the cradle. Take care to carefully remove the double sided tape from the midge before doing this. Once the midge is removed, you can stop the recording from your laptop, and then extract the SD card from the midge which is where all the relevant data will be. 

