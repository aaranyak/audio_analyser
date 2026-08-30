# Musical Instrument Sound Analyser Tool

### Description
*This is a program for analysing sounds of musical instruments. The tool can read `.wav` files, and then perform frequency analysis, and amplitude analysis on them. The program contains two tools: A spectrogram generator for frequency analysis and, a tool which displays an amplitude/time graph for each frequency component in the signal*

### Audio Analyser
<img width="1840" height="282" alt="image" src="https://github.com/user-attachments/assets/c577e424-e077-46ec-96ad-7ad1c31d765c" />

*The `.wav` file is loaded by pressing the button on the top left, and a waveform is displayed. Some audio metadata is displayed on the top right, and the sliders on the bottom can be used to trim the length of the audio being analysed*

### Spectrogram Generator
<img width="1428" height="589" alt="image" src="https://github.com/user-attachments/assets/617df5b8-6a85-40b3-ae4d-007da4765a6c" />

*This tool generates a spectrogram from the trimmed region of the audio file. The buttons below, from left to right respectively are*

 1. Offset between each time-domain segment of the spectrogram
 2. Length of each time-domain segment of the spectrogram
 3. Minimum frequency displayed on the spectrogram
 4. Button to generate the spectrogram.
 5. Info regarding the mouse cursor position
 6. Slider to change the amplitude range displayed on the spectrogram.

### Amplitude Graph Generator
<img width="1835" height="737" alt="image" src="https://github.com/user-attachments/assets/a3c26a88-17ec-4517-bf29-ed21290da5c7" />

*This tool splits the audio signal into it's component frequency components using an FFT and bandpass filters, and plots the amplitude of each of them over time. Buttons, from left to right, top to bottom*

 1. Number of frequency components to display
 2. Lower bound of search frequency range
 3. Higher bound of search frequency range
 4. Minimum gap between each frequency component
 5. Size of the bandpass filter
 6. width of the bandpass filter
 7. Frequency of the lowpass filter
 8. Scaling factor for the graphs
 9. Button to generate the graphs
 10. Mouse cursor position on the graph
 11. Number of sample points when exporting the graphs
 12. Button to export the graphs as CSV
