# MCSD-Disassembly-Screw-Dataset
We constructed a dedicated multi-class screw detection dataset, termed MCSD (Multi-Class Screw Detection).   The dataset contains 1240 images covering 12 screw categories, all annotated using LabelImg.   The parameter specifications of each screw type are summarized in the following table:  
<img width="599" height="504" alt="image" src="https://github.com/user-attachments/assets/bb1a63dd-d39d-4f18-a560-1698430b0d06" />

***Examples from the dataset***:  
<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/9629cb65-6c22-47e7-895d-d7ae9df76324" />

The MCSD dataset presents the following challenges:  
**(1) inter-class similarity and intra-class variability are significant**.  The screws exhibit a wide range of sizes (M4–M8, with head diameters from 7 mm to 13 mm) and diverse types (six main categories), which leads to high inter-class similarity. In addition, deformation, wear, and other physical conditions introduce significant intra-class variations in appearance.  
**(2)Environmental interference further complicates detection**. The disassembly environment often involves drastic illumination changes, motion-induced image blur from the robot, and partial occlusion or incomplete capture of the target objects, all of which increase the difficulty of accurate screw detection.  
Consequently, MCSD provides a challenging benchmark for researchers to objectively evaluate and compare the performance and robustness of their screw detection models.

**MCSD Dataset can be downloaded through this link**:  
[MCSD Dataset](https://drive.google.com/file/d/1edOEWQQsI6ifmYKgOUi3PvgIC-k8pN31/view?usp=drive_link)

