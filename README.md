# pupil_eyes

Run experiments and record eye-tracking data from Pupil Labs hardware in MATLAB.

To use:

1) Install ZMQ 4.0.x: http://download.zeromq.org/#ZeroMQ_4

2) Point to ZMQ in the config.m file of matlab-zmq

2) Install matlab-zmq: https://github.com/fagg/matlab-zmq

3) Install msgpack https://github.com/bastibe/matlab-msgpack

4) Edit `pupil_remote_control.m` to include your experiment where indicated in the file

5) Open Pupil Capture

6) Run `pupil_remote_control.m`

7) Open and use Pupil Player to export the raw-data in CSVs https://docs.pupil-labs.com/core/software/pupil-player/#export
