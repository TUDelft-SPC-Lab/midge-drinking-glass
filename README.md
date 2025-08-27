# Smart Drinking Cups
This is the public repository for the Smart Drinking Cups open hardware. 

## Project Overview
### Rationale
The cup provides a practical way to embed sensing technology into a familiar everyday object, allowing researchers to study human behavior in  a natural social setting.
By holding the SPCL Midge Badge in a consistent and unobtrusive position, the design ensures reliable data capture of formats like audio, proximity and motion data, while maintaining the normal function of a drinking vessel.
This approach can be replicated in other contexts where seamless integration of sensors into daily activities is needed.

### Hardware
The following components are needed to assemble a cup:
- [Zara home cups](https://www.zara.com/nl/nl/recht-kristallook-drinkglas-p40254402.html)
- [Transparent silicon sleeves](https://web.archive.org/web/20250827082532/https://www.amazon.nl/dp/B0BVFHP79J?ref=ppx_yo2ov_dt_b_fed_asin_title)
- A transparent cradle. This was 3d printed by us, with xxxx filament. The design file can be found [here](midge_2%202025-05-19%2009-57-53%2019%20May%202025%2009-57AM.stl)
- [SPCL Midge Badges](https://github.com/TUDelft-SPC-Lab/spcl_midge_hardware)
- Double sided tape (optional)

### Assembly

The Smart Cup can be assembled by:
1. Turn the midge on and placing it in the cradle.
2. Attach attaching double sided tape to the midge.
2. Ensure that the midge is resting on the extruding bit of plastic at the bottom of the cradle.
3. Then the cup should be placed above the cradle, and you should push the midge upwards from the opposite hole of the cradle, so that the tape sticks to the bottom of the cup.
4. Then the whole thing should be pressed into the sleeves tightly. 
5. Ensure that the cradle and cup are straight and coincide with one another.

## Operation

To start the data collection follow this procedure after assembling the cup:
1. Follow the start recording procedure described [here](https://github.com/TUDelft-SPC-Lab/midge-code?tab=readme-ov-file#recording-data).
3. Perform the experiment. The cup should be filled with liquid, and can be used as a normal drinking cup.
4. When the experiment is done, any liquid in the cup should be removed.
5. Take the cup out of the sleeve.
7. Carefully remove the double sided tape from the midge.
6. Extract the midge from the cradle.
7. Stop the recording by turning off the sensors.
8. Follow the data extraction and processing procedure described [here](https://github.com/TUDelft-SPC-Lab/midge-code?tab=readme-ov-file#recording-data).

