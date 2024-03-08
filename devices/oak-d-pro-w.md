# OAK-D Pro W

The device arrives with stereo/rgb cameras calibrated but IMU is not calibrated.
The eeprom calibration has distortion model rational-polynomial, this is not always supported depending on packages (RPG SVO Pro vio..).

## Calibrate IMU
use package https://github.com/ori-drs/allan_variance_ros.git to calibrate the IMU, bag the imu topic.

## Calibrate IMU + Stereo cameras
use Kalibr https://github.com/ethz-asl/kalibr
