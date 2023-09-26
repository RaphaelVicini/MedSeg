# Execution

Once the setup is complete, users can simply click on `medseg_exe.py` to run MedSeg on their laptop. The browser will automatically open with the appropriate URL, taking users directly to the MedSeg login page.

# Connection 

Users should enter their username and password to access MedSeg.

# Inside MedSeg 

## Creating a New Project

1. Click on the green "Add Project" button.
2. Enter your desired project name.
3. Press "OK".

## Uploading Files 

1. Click on the blue "Upload" button.
2. Select the images you wish to upload.

**Important**: 
- If you're using an image as a primary image or as a mask, their filenames must differ.
  - For a primary image, the naming format should be: `img_MYIMAGE`
  - For the mask of this image, it should be: `msk_MYIMAGE`.
  
  "MYIMAGE" can be replaced with any desired name, but ensure the identifier remains consistent between an image and its corresponding mask.
  
- Files must be in the `.nii.gz` extension. (nifti format ONLY)

- You can put many images at the same time

<img src="./pictures/img_upload_img.png" alt="Example Image" width="1500" height="150"/>

