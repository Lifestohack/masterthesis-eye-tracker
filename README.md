eye_tracking: used to calculate accuracy and create video experiments. Normally Pupil Labs Capture software has this feature. There is also a Pupil Labs Player plugin to export the calibration markers position from world camera.

ffm_zmq: used to test the ffmpeg to read video from a webcam. Draw histogram with time vs frequency graph, average exposure time and client read time from network.

smartglass: used to test Pupil Labs pupil-detector algorithm in raspberry pi. This is the strip down version without any GUI.

pupil-video-backend: Used to stream eye video from raspberry pi to a client. With network_latency.py you can calculate one direction Network latency calculated between PVB and Pupil Labs Capture Software.
