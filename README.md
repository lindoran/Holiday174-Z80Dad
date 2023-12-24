# Holiday174-2023

A Very Simpe 4 state machine on a 74hc73, this is a multivibrator on 2 1n2222 transistors (similar PNP may work).  

<h3>The contest rules are simple:</h3>
 
 1.) build a decoration using only one 74 Series IC.<BR>
 2.) it you may use two descrete transistors.<BR>
 3.) you may use any number of passives: coils, capacitors, diodes, and resisters. <BR>
 4.) you may use LED's, Lamps, or Neon's as a light source.<BR>
 5.) only external connection can be the power source.<BR>
 

 <h3>Rest of the rules here are in this facebook post:</h3> 
<P>
   HOLIDAY DESIGN CONTEST IDEA: Now that thanksgiving is fully out of the way (at least for us in NA, Canada has theirs in October!) I was thinking about a one month holiday decoration design competition. What can you make with one 74 series IC (any family HC, LS, ect..) and two discrete transistors max. This can be breadboard, strip board (proto board) point to point, wire wrap, simulation or PCB.  You can use as many support passives as you like but the only external connection should be power. VCC can be any supported voltage source that your 74 series IC can use. No other IC packages can be used this includes 3 pin ic packages which look like but are not discrete transistors. For the purposes of this contest passives are defined as capacitors, resistors, diodes and coils (LEDs that flash on their own are exluded -- nice try).  For fun light sources Lamps, Neons (heh lots of current but you do get two transistors) and regular non blinking LEDs.(clarification LEDs in the project can blink but the part itself can not blink on its own with only applied power.) Submissions should contain schematics, and pictures of a working prototype. Again simulation is 100%  ok, however it can not contain a proxy input or device such as, but not limited to: an external clock, lookup or fsm. Only 1 IC and two discrete transistors + allowed passives and a voltage source / ground.  Lastly - this is only 74 series ic's ( ie ic's which have 74(family name )series number in the part number. Also I should not have to say this but designs should be new, and original (as possible -- I realize some reference designs are close to perfect for this) Submissions judged as they come in by the community and we deicide as who reins supreme on January 1st (just bragging rights, but hey this sounds fun to me!)  Simply put #HOLIDAY174 in your submission so we can search it at the end of the contest.   REMEMBER 1 74 SERIES IC AND 2 TRANSISTORS MAX! OH AND ALSO HAVE FUN 😁
</P>
<br>
<h3>Here's my submisson:</h3>
<img src="3D TOP.png">

<P>Esentally, the circut is a div by 4 clock divider.  However, instead of a traditional d-latch I have used a J/K Flip flop.  This has the benifit of creating 4 output clocks that are 90 degrees offset from eachother. In adition to the offset clocks I used a few DRL and gates to create a and of Q1 and Q2, as well as, Q1_ & Q2_. The advantage to using this IC is that it has a falling clock trigger, which is also a Shmidt Trigger. Since the multivibrator is at its heart a RC, we can avoid triggering off the rising edge of the clock, as it is more round than flat. </P>

<P>The project is powered by a pair of CR2032 battiries in series.  I used a 1N4007 rectifier diode, to previent accidentaly reversing the voltage from the pack.  The 74HC73 package itself supports a VCC of 6 volts, however the diode has a forward drop of about .8 volts. I also ended up building a few of these as gifts, and experimented with a few alternate parts.  Instead of Zener Diodes I tried using standard rectifier diodes for the and gates which worked and most likely reduces the cost further.</P>

<h3>Here is a small <a href="https://www.facebook.com/1557231165/videos/1525780231489265/" target="_blank">reel</a> of the oriment in action:</h3>


 
