# <p align="center"> Driver Alert System </p>

### Warns the driver when he/she is drowsy.

The driver anomaly observing framework created is able to identify laziness and distraction of the driver. The Laziness Detecting Framework created based on eye and mouth ratios of the driver can identify tiredness and distinguish the laziness while driving. The suggested device is able to avoid the incidents when driving due to sleepiness. The system works properly even in case of drivers sporting spectacles and even below low light stipulations if the digital camera offers higher output. Information about the eyes and mouth position is obtained through a range of self-developed photograph processing algorithms. During the monitoring, the system is able to figure out if the eyes and mouth are opened or closed. When the eyes have been closed for too long or the mouth has been opened for too long, a warning sign is issued using the alarm.

## Methodology
- If the eyes of drivers are closed for a threshold period of time (i.e. the EAR (Eye Aspect Ratio) < threshold value) then it is considered that the driver is feeling sleepy and a corresponding audio alarm is used to make the driver aware.
- If the mouth of the driver remains open for a certain period of time (i.e. the MAR (Mouth Aspect Ratio) < threshold value) then it is considered that the driver is yawning and corresponding suggestions are provided to the driver to overcome drowsiness.
- If the driver doesn't keep eyes on the road then it is observed using facial landmarks and the corresponding alarm is used to make the driver aware.

## Technologies Used
- Python
- scipy
- imutils
- pygame
- dlib
- cv2
