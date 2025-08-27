# Smart Drinking Cups
This is the public repository for the Smart Drinking Cups open hardware. 

## Project Overview
### Rationale
The cup provides a practical way to embed sensing technology into a familiar everyday object, allowing researchers to study human behavior in  a natural social setting.
By holding the SPCL Midge Badge in a consistent and unobtrusive position, the design ensures reliable data capture of formats like audio, proximity and motion data, while maintaining the normal function of a drinking vessel.
This approach can be replicated in other contexts where seamless integration of sensors into daily activities is needed.

### Hardware
The following components are needed to assemble a cup:
- [Zara home glasses](https://www.zara.com/nl/nl/recht-kristallook-drinkglas-p40254402.html)
- [Transparent silicon sleeves](https://web.archive.org/web/20250827082532/https://www.amazon.nl/dp/B0BVFHP79J?ref=ppx_yo2ov_dt_b_fed_asin_title)
- A transparent cradle. This was 3d printed by us, with xxxx filament. The design can be found [here](midge_2%202025-05-19%2009-57-53%2019%20May%202025%2009-57AM.stl)
- [SPCL Midge Badges](https://github.com/TUDelft-SPC-Lab/spcl_midge_hardware)
- Double sided tape (optional)

The software required for the initialization of the midge and its software can be found both in its [hardware](https://github.com/TUDelft-SPC-Lab/spcl_midge_hardware) and [software](https://github.com/TUDelft-SPC-Lab/midge-code) repositories. 

### Assembly / Getting Started
1. The Smart Cup can be assembled by first turning the midge on and placing it in the cradle then attaching double sided tape to it. 
2. Ensure that the midge is resting on the extruding bit of plastic at the bottom of the cradle
3. Then the glass should be placed above the cradle, and you should push the midge upwards from the opposite hole of the cradle, so that the tape sticks to the bottom of the glass
4. Then the whole thing should be pressed into the sleeves tightly. 
5. Ensure that the cradle and glass are straight and coincide with one another


## Operation

During assembly the midge should have been left on.
In this case following the instructions of the midge initialization, you can connect to the midge via the code in [this](https://github.com/TUDelft-SPC-Lab/midge-code) repository.
After connecting to the midge via the interface of your choice, you can turn on the microphone/IMU/Bluetooth sensor data and the midge will begin recording, so you can use the glass as you wish. 

When the experiment is done, any liquid in the glass should be removed, and the glass should be taken out of the sleeve.
After this the Midge can safely be extracted from the cradle.
Take care to carefully remove the double sided tape from the midge before doing this.
Once the midge is removed, you can stop the recording from your laptop, and then extract the SD card from the midge which is where all the relevant data will be. 

