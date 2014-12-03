Buffer-based Videostreaming Simulation
======================

This set of Python scripts can be used to simulate the fill level of a video buffer during progressive streaming. It works by comparing a video frame list to a prerecorded network trace.
The behavior of the buffer can be controlled through a number of playback strategies, which emulate real-world behavior, e.g. that of the YouTube Flash Player.
The scripts will either output a time-series of the fill level or additionally just aggregate the number of stalling phases and their durations with the selected strategy. This allows for an easy comparison between strategies, network conditions or videos.

These scripts were previously used to retrieve YouTube videos by crawling their early 2013 Website structure and trace the transmission.
