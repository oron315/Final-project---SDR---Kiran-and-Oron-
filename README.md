# Final-project---SDR---Kiran-and-Oron-
The files discriptions:

demod_samp2str.py - Python file of the block that receives bits and translates them to the text message according to the protocol, no FM.

mod_source_str2samp.py - Python of the modulation block that takes a string and sends the bits according to the protocol, no FM.

report-transfering text data with audio.pdf - pdf the explains the project, step by step.

test_demod_info.grc - tests to see if sending a message is received, and decoded how it should.

test_recive_audio.grc - flow graph to receive the audio and find the message from it.

test_send_audio_hilbert.grc - flow graph to simulate the whole process of sending an FM modulated audio signal, adding noise, and the reciving and decoding the message.

test_transmit_audio.grc - flow graph to transmit the audio after FM modulation of our message.
