# Pocket Operator Syncing Web Synth

A simple example how to use the Web Audio API to sync up one of teenageengineering ([@jugendingenieur](https://twitter.com/jugendingenieur)) Pocket Operators (PO-12, PO-14, PO-16) to a simple sequencer/synthesizer.

(You have to bring your PO into SY4 (if you only attach a single PO) or SY5 (if you attach a few PO's chained) mode by repeatedly pressing FX + BPM).

This was mostly meant as a test if the audio levels are good enough to drive the sync input. After that I figured I might as well add some synth to test the "sidechain" input mode. So this outputs the sync signal on one stereo channel (L) and the synth signal on the other (R).
