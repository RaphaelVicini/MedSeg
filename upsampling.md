# Upsampling

Users have the capability to perform upsampling.

**How it works:** If the user places some dots on the image and categorizes the mask as "upsampling", the script will crop around the dot, forming a cube of 10cm³, unify the voxels, and then upscale this cube.

The primary objective of this upsampling is to enable users to magnify a section of an image. This way, they can view finer details.

**Note:** 
- Users should use one label per dot. If a single label is used for two dots, the code will compute the mean value of the center of the two dots. 
- Multiple dots can be upscaled simultaneously. When a unique label is used for each dot, the script will upscale all the dots, producing a number of images equal to the count of labels/dots used.
- Upscaled images will be named incorporating both the label number used and the SeriesUID of the original image, following this pattern: `CroppedUp-Label_1-From_SeriesUID`.

- The images produced post-upsampling users can either employ the MedSeg tool to segment and potentially create a model specifically for the upscaled images.

## Run the Upsampling

To initiate the upsampling process, users simply need to double-click on the image. If the mask is categorized as "upsampling", the upscaling will automatically commence. After a few seconds, the upscaled images will be generated.
