# jointlydeblur
jointly deal with local(objects) and global(camera) motion blur in a dynamic scene

background:
single image of dynamic scene with global camera motion and local object motion

contributions:
1.  degradation model, local motion is the relative motion between camera and object, so it is the combination of camera and object motion
2.  the motion blur effect of each pixel should be considered as the time and space integration of the motion.
3. solve the dynamic scene deblurring problem with global constraints.
