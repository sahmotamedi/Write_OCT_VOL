# Write_OCT_VOL
A MATLAB script to write *.vol files as formatted by Heidelberg Engineering spectral domain optical coherence tomography (SD-OCT) device.

Heildelberg Engineering (HE) is one of the most dominent SD-OCT manufacturers for retinal imaging (there is a SD-OCT from Heidelberg Engineering in the International Space Station [(ISS)](http://www.octnews.org/articles/5179109/heidelberg-spectralis-oct-eye-examinations-in-spac/)!). SD-OCT images from HE are usually saved in an standard format named E2E, though HE has another file format to save OCT images, *.vol format, which it has only given to some research groups. The code to read *.vol files have been written, and now this project consists of a MATLAB code (*.m file) to write *.vol files. 

The Write_OCT_VOL might be useful if someone wants to modify OCT images or their information (cropping images, changing the segmetation, etc) and afterwards save them again in the .vol format.

In this repository, I have also included a MATLAB code to read *.vol files, which was originally writen by Radim Kolar, Brno University, Czech Republic, modified by Markus Mayer, Pattern Recognition Lab, University of Erlangen-Nuremberg, and modified by me, Seyedamirhosein Motamedi from Charité - University Medicine Berlin. 


## Usage

To run this code, MATLAB R2012b or later is needed, without the need to install any additional MATLAB Toolboxes. An instruction on how to call the write_vol function in MATLAB and more details about this fuction are provided at the beginning of the write_vol.m file. 

## License 

Please read LICENSE.txt.
