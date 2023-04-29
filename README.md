<h1 style="text-align: center;"><strong># Biqu-B1_Custom_Firmware</strong></h1>
<p><strong>Disclaimer: I am not developer or owner either for Marlin or Bigtreetech, I just compiled my own firmware and sharing with others who do not want or do not have knowledge to do their own. Please do not make me responsible for any problem on your printer.<br /></strong></p>
<p><strong>I have a B1 with SKR 2 REV B with F407 processor, so for other version, I didn't test the firmware. Any problem please let me know.</strong></p>
<p>&nbsp;</p>
<h2><span style="color: #ff0000; background-color: #999999;">Klipper for the BIQU B1:</span></h2>
<p><span style="color: #993366; background-color: #999999;"><strong>As I have started experimenting with Klipper, I have uploaded my configs files to share with our coleagues owners of BIQU B1 with the SKR2.</strong></span></p>
<p><span style="color: #993366; background-color: #999999;"><strong>Please be aware that the configs and the macros were developed to my specific use, so please review all the items before start using in your printer. Any doubts please contact me.</strong></span></p>
<h2>&nbsp;</h2>
<h2>Lastest Marlin version: 2.1.2</h2>
<ol>
<li>
<blockquote>Marlin 2.12 introduces the Input Shaping experimental feature, I enabled in firmware for testing and is being working. Any bug please advise.</blockquote>
</li>
<li>
<blockquote>Also the Developers from Marlin had corrected the Linear Advance feature to work with TMC 2208 driver which enable our Biqu B1 to make advantage of this feature 2. I have enabled also in firmware.</blockquote>
</li>
</ol>
<h2><br />Pre-compiled firmware updates from Marlin Github for BIQU B1 printer:</h2>
<p>Customized from original Marlin repository, with last configuration.h files from BIQU</p>
<p>Recommend the UBL Version if you have BLTouch.</p>
<blockquote>
<p>Instructions:</p>
</blockquote>
<ol>
<li>
<blockquote>Please follow below instructions to calibrate the Input shaping and Linear advance features:<a href="https://marlinfw.org/docs/gcode/M593.html">https://marlinfw.org/docs/gcode/M593.html</a> and <a href="https://marlinfw.org/tools/lin_advance/k-factor.html">https://marlinfw.org/tools/lin_advance/k-factor.html</a></blockquote>
</li>
<li>
<blockquote>Check e-steps before start printing, the default e-steps was adjusted for the original extruder.</blockquote>
</li>
<li>
<blockquote>Z-homing probing was back to the center of the bed, due to inconsistence in the mesh.</blockquote>
</li>
<li>
<blockquote>For BLTouch firmware, the NOZZLE_TO_PROBE OFFSET is adjusted to the one in Thingiverse. <a title="THIS THING" href="https://www.thingiverse.com/thing:4564987">https://www.thingiverse.com/thing:4564987</a></blockquote>
</li>
</ol>
