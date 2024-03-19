# LabviewGetColormap

A subVI featuring pre-defined colormap arrays to use as inputs to Labview graph colortable property node to select from one of 6 colormaps from MATLAB or Matplotlib: Grayscale, Jet, Hot, Viridis, Parula, and Plasma.

 ## Table of Contents

- Requirements
- Installation
- Datasets
- Usage
- References
- License

## Requirements

GetCmapArrays.vi requires Labview 15.0 or newer. GetCmapArrays.vi is designed to be used in conjunction with a VI featuring a front panel display item with the "Colortable" property.

## Installation

Add GetCmapArrays.vi to a folder in the path of the intended parent VI.

## Usage

Add GetCmapArrays as a subVI to the block diagram of the intended parent. Wire the desired colormap output to a "Colortable" property node of the intended front panel display node. See example images "LVcmapBD.PNG" and "LVcmapFP.PNG" for how this VI can be used in conjunction with an enumerated case structure to change colormaps programmatically.

## License