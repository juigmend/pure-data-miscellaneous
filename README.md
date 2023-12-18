# Pure Data miscellaneous

<img src="https://gitlab.jyu.fi/juigmend/pure-data-plethora/-/raw/main/pd_loop.png">

Miscellaneous <A HREF="http://puredata.info/">Pure Data</A> patches.

<img src="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/raw/main/AALTOJA_helmikuuta_2017.mp4" width="280" height="270">

<A HREF="https://gitlab.jyu.fi/juigmend/pure-data-plethora/-/blob/main/Pd_instrument/Instrument/Instrument_Aaltoja_WORK.pd">Aaltoja - Pd patch</A>

## Description 

<ul>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Pd_intro_tutorial_nov_2017.zip">Pure Data Introduction Tutorial.</A>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Musical_Instrument_Dataflow_Programming.zip">Musical Instrument Dataflow Programming</A>
is intended to help in learning to design a software musical instrument.   
 It consists of a Puredata main patch and abstractions. 
 Includes tools for Control, Mapping and Audio Synthesis. 
 Control: OSC data and Human Interaction Interfaces (Wiimote, Mouse, USB joystick, keyboard, etc.). 
 Mapping: Control signal processing such as Rescaling, Invert, Smooth and Shake detection. 
 Audio Synthesis: Audio Input, Fire generator, Filter, Looper, Granulator. 
 Also includes a colourful graphical user interface made with dynamic patching.
 </li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/heatmap.pd">Heatmap</A> of a 2D matrix (abstraction).</li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/novelty.pd">Novelty </A> score of a control signal. 
Requires the following abstractions in the same directory or folder, or in other declared path:</li>
	<ul><blockquote>
	<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/square_window.pd">Square Window</A></li>
	<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/gaussian_checkerboard_kernel.pd">Gaussian Checkerboard Kernel</A> 
	Requires the following abstractions in the same directory or folder, or in other declared path:</li> </li>
		<ul>
		<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/gaussian_kernel_2D.pd">Gaussian Kernel 2D</A> 
			Requires the following abstraction in the same directory or folder, or in other declared path:</li> </li>
			<ul><blockquote>
			<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/meshgrid.pd">Meshgrid</A> </li>
			</ul>
		<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/checkerboard_matrix_2D.pd">Checkerboard Matrix 2D</A> </li>
			Requires the following abstraction in the same directory or folder, or in other declared path:</li> </li>
			<ul><blockquote>
			<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/kron_2D.pd">Kronecker Tensor Product 2D</A> </li>
			</ul>
		</ul>
	</ul>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/gauss_filter.pd">Gaussian Filter </A> of a control signal. 
Requires the following abstractions in the same directory or folder, or in other declared path:</li>
	<ul><blockquote>
	<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/square_window.pd">Square Window</A></li>
	<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/gauss_window.pd">Gaussian Window</A></li>
	</ul>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/moving_average_filter_demo.pd">Moving Average Filter Demonstration</A> shows moving average filters as numerical integration. 
Requires the following abstractions in the same directory or folder, or in other declared path:</li>
<ul><blockquote>
<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/am_wavegen.pd">AM wave generator</A> </li>
<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/oscilloscope.pd">Oscilloscope (small size)</A> </li>
</ul>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/basic_kinematics_demo.pd">Kinematics Demonstration.</a>
Requires the following abstractions in the same directory or folder, or in other declared path:</li>
<ul><blockquote>
<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/oscilloscope.pd">Oscilloscope (small size)</A> </li>
</ul>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/simple_plot.pd">Simple Plot (medium size)</A> is an abstraction to plot a control signal, has a "thru" output.</li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Visuaural_v0.1.5.pd">Visuaural version 0.1.5</A>,
 <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Visuaural_v0.1.4.pd"> 0.1.4</A> is a programmable tool for presenting stimuli and recording data in different modalities. 
Documentation: <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Visuaural_v0.1.4_readme.txt">v0.14</A>
 <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Visuaural_v0.15_readme.txt">v0.15</A>.</li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Audio_Video_Player_v0_2.pd">Audio and Video Player version 0.2</A> 
plays Audio and Video allowing to scroll back and forward, change speed and retrieve SMPTE code. Useful for audiovisual annotation.
Documentation <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Audio_Video_Player_v0_2_readme.txt">here</A>.
</li>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Only_Video_Player_v0_1.pd">Only Video Player version 0.1</A> 
plays Video allowing to scroll back and forward, change speed and retrieve SMPTE code. Useful for video annotation.
Documentation <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Only_Video_Player_v0_1_README.txt">here</A>.
</li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Myo_OSC.pd">Myo OSC v2 (abstraction)</A>, 
<A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/OSC_receive_MYO_43_4.pd">OSC Receive MYO for Puredata Extended v0.43.4 (patch)</A>  and 
<A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/OSC_receive_MYO_42_5.pd">OSC Receive MYO for Puredata Extended v0.42.5 (patch)</A>  
receive data coming from the <A HREF="https://www.myo.com">Myo armband</A> via OSC.
</li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Record_Wii_Myo_Audio_v0.1.2.pd">Record Wii+Myo+Audio version 0.1.2  </A> 
records data from OSC (e.g., a Nintendo Wii-remote or a Thalmic Myo armband) and 2 channels of audio 
(e.g., one for stimulus and the other for a synchronisation signal). It can be synchronised to an external trigger (e.g., Qualisys QTM motion capture).
Documentation <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Record_Wii_Myo_Audio_v0.1.2_readme.txt">here</A>.

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Record_Wii+Audio_v0.1.3_beta.pd">Record Wii+Audio version 0.1.3_beta </A> 
records data from OSC (e.g., a Nintendo Wii-remote) and 2 channels of audio 
(e.g., one for stimulus and the other for a synchronisation signal). 
Documentation <A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Record_WII+Audio_v0.1.3_beta.txt">here</A>.
</li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Audiofile_Rating_v0.1.2.pd">Audiofile Rating</a> Presents audio stimuli and records user's rating.
Documentation <a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/Audiofile_Rating_v0.1.2_README.txt">here</a>.
</li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/pääsiäispuputuksia.zip">Pääsiäispuputuksia</a> Shows how to manipulate graphic files with GEM. 
Help the bunny to get fatter by eating chocolate eggs. Includes bunny and chocolate eggs. </li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/TCP_networking_demo_v0.2.pd">TCP Networking Demonstration</a> Shows how to send and receive messages through a TCP network.</li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/discretize_a_continuum_v0.1.pd">Discretize a Continuum Demonstration</a> 
Shows how to chop a continuum into sections. Useful to map a continuous motion signal to musical notes.</li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/segment_concatenator_v0.1.pd">Segment Concatenator</a> 
Shows how to continuosly play non-consecutive segments of an audio file, like <a href="https://www.ableton.com/">Ableton Live</a>.</li>


<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/record_elapsed_time_DEMO.pdf">Record playbcak elapsed time</a>  of a sound file.</li>

<br>
<li><a href="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/metronome.pd">Metronome</a></li>

<br>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/shake.pd">Shake</A> measures activity of a control signal. 
For example, it can be used to measure the shaking of accelerometer data.
</li>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/simplestereolooper.pd">Simple stereo looper</A> 
has a binary control. 1 records stereo audio erasing previous recording. 
0 stops recording and plays back in a loop.
</li>

<li><A HREF="https://gitlab.jyu.fi/juigmend/pure-data-miscellaneous/-/blob/main/rescaler.pd">Rescaler</A> 
of control signals. It takes the following variables: input maximum, input minimum, 
desired output maximum and desired output minimum.</li>

<br>

<li><A HREF="https://yousource.it.jyu.fi/meetings">Disembodied Speculations</A> 
 is a project to make music using computers. It has an online 
 <A HREF="https://yousource.it.jyu.fi/meetings/meetings/trees/master">repository</A> of <A HREF="http://puredata.info/">Pure Data</A> patches and 
<A HREF="http://supercollider.github.io/">Super Collider</A> scripts.</li>

</ul>

## License
All software of my authorship in this page is published under the <a href="https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html">GNU General Purpose License version 2.</a>
