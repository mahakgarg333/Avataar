Object Segmentation

Object segmentation is the process of identifying and isolating a specific object within an image. 
In this case, we use a pre-trained segmentation model, such as the Segment Anything Model (SAM), to segment the object based on a user-provided class prompt.
The SAM model uses a combination of convolutional neural networks (CNNs) and transformers to learn a representation of the object and the background. 
The model is trained on a large dataset of images with annotated masks, which allows it to learn the patterns and features that distinguish objects from the background.

Pose Editing

Once the object is segmented, we use a generative model, such as Stable Diffusion, to edit the pose of the object. 
Stable Diffusion is a type of diffusion-based generative model that uses a process called denoising to generate images.
The model takes the segmented object and the desired pose as input and generates a new image with the object in the desired pose. 
The model uses a combination of CNNs and transformers to learn a representation of the object and the pose, and then uses this representation to generate the new image. 

FOR TASK 1 THIS IS MY INPUT IMAGE 

![image](https://github.com/user-attachments/assets/65170332-dd34-4a09-b932-b83643ccfcff) 

THIS IS MY OUTPUT 

![image](https://github.com/user-attachments/assets/5ccd2720-4802-4045-bac2-cf88787fa84b) 

FOR TASK 2 THIS ARE MY OUTPUT IMAGES 

![image](https://github.com/user-attachments/assets/5c0ea723-18cb-45b2-aa9f-bde4d8f59033)

![image](https://github.com/user-attachments/assets/92f59001-b9fa-41a9-ba39-9b7a68c51b18)

