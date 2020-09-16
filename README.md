# Motion detector

Background subtraction is used for detecting dynamically moving objects from static camera.
  
More specific, in this project, Running Average is a technique for background(bg) subtraction.
  
Running Average: bg = (1 – α) * bg + α * image.
  
Background is accumulated through entire process. To detect motion, we compute the absolute difference between the image and the bg.
  
The smaller α is, the more sensitive the system is to motion.

# Output example
https://github.com/daoducanhc/motion_detector_/blob/master/Frame%202020-05-15%2014-10-11.mp4
