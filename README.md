# wordImageGenderator
random word image genderator with pytorch Dataset utils

# requirements
* pytorch
* torchvision
* Pillow
* opencv-python
* tqdm

# Prepare Dataset

1. Download font images. 
http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/EnglishFnt.tgz. 

2. Crop font images with no margin. 
<pre>
<code>
python crop_font_image.py --dir_path='font images dir path' --target_path='path to target dir'
</code>
</pre>

3. Use dataset generator

