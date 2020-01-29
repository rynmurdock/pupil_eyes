# pupil_eyes

Run experiments and record eye-tracking data from Pupil Labs hardware in MATLAB.

To use:

1) Install ZMQ 4.0.x: http://download.zeromq.org/#ZeroMQ_4

2) Point to ZMQ in the config.m file of matlab-zmq

2) Install matlab-zmq: https://github.com/fagg/matlab-zmq

3) Install msgpack https://github.com/bastibe/matlab-msgpack

4) Edit `pupil_remote_control.m` to include your experiment where it is indicated in the file

4) Run `pupil_remote_control.m`

5) Use Pupil Player to export the raw-data CSVs https://docs.pupil-labs.com/core/software/pupil-player/#export
