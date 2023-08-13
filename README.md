# lane-follower

Given a video file, we need to instruct the bot whether to go left,right or stay on the track. This is usefull for a typical lane follower robot.
This code reads frames from a video file, applies a color-based mask to detect a certain color range (presumably a line), finds contours in the mask, calculates the centroid of the largest contour, and based on the centroid's position, determines whether the line-following robot should turn left, go straight, or turn right.


