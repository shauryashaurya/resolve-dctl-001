# resolve-dctl
Color Transform Lanaguage library providing transforms for Davinci Resolve

Includes:

* S-Curves - Generate S-Curve using various Sigmoid functions
* Mid-Highlight - Green Highlight on Middle Gray at 18% reflectance (40.5 IRE) or selectable IRE at Data Levels
* Mid-Select - Show Mid Gray at 18% reflectance (40.5 IRE) or select IRE at Data Levels; everything else Black
* Blackout - Black Out specified area based on luma
* Whiteout - White Out specified area based on luma
* full2legal - Convert Data signal to Video levels using proper quantization equation
* legal2full - Convert Video signal to Data levels using proper reverse quantization equation


Transforms use Rec.709 Color Primaries where applicable.
Most DCTL files can be used with either a Scene or Linear timeline gamma.


## Installation
Save the DCTL files to the relevant locations based on the host Operating System as noted below:

#### Windows
C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT\

#### Mac
/Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT

#### Linux
/home/resolve/LUT

