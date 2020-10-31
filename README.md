# Submarine-Surfers
## HackOverflow
Object detection model to find the center of the gate under water - PROTOTYPE



**Team Name:** Deep-AI

**Team Members:**
      1. Shouhaddo Paul
      2. Thirumalai Kumar
      3. Bala Ganesh R


**Steps For Inference:**
1. clone the repository using !git clone.
2. Open the notebook file and use the predefined function to predict the center of the gate.
3. Functions and it's roles:
    * run_inference_single_image(model,image): provide the model and image loaded by opencv, this function will give you the detected_classes,scores and box coords.
    * show_inference(model,frame): Function with tensorflow vis_utils to draw the bounding box alone.
    * post_process_bb(model,img,threshold=0.5): function that will find the classes,box_coords and scores.Just an implementation from scratch for the purpose of finding centerpoint of the gate.
    * midpoint(): This is the main function that gives you the centerpoints of the gate after detection.

