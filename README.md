# cv-face-tracking


Race - thoughts
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
40,000ft plan

~~[OpenCV](https://opencv.org) or [OpenFace](https://cmusatyalab.github.io/openface/)???~~~ --> [Neural Similarity](https://peltarion.com/blog/data-science/image-similarity-explained) to the missing persons.

I like the idea of making a Neural Similarity models because then we don't need lots of images for the predicted persons. Just one image. How would we get a Null class? Would the null class just be the model not passing a confidence threshold for any class?

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Colin Thoughts**
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
[Detectron2] https://github.com/facebookresearch/detectron2 - Built by Facebook and integrated with Pytorch for facial recognition and tracking. Race- this is sick this is for sure what we want


Questions Race has:
- Ok I can classify entities in a picture but what do I do for a video? 
- Frame by frame and treat them like images? 
- The video is a tensor the images are the layers of tensor? 
- Does Detectron do video?
