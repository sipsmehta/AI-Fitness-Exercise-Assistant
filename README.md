# Body-Pose-Estimation-in-Simple-steps-Using-OpenCV
## I came across a topic to be considered as a help for gym freaks. People who are into fitness does not want to be lenient in their sets or reps count. For this I had developed a Rep counter that is using some #computervision techniques and libraries. In this technique I had used the formula of:

# The formula used to find angle is as follows
  radians = np.arctan2(c[1]-b[1], c[0]-b[0]) - np.arctan2(a[1]-b[1], a[0]-b[0])
  angle = np.abs(radians*180.0/np.pi)
