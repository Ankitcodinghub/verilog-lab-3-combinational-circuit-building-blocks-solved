# verilog-lab-3-combinational-circuit-building-blocks-solved
**TO GET THIS SOLUTION VISIT:** [Verilog Lab 3-Combinational-Circuit Building Blocks Solved](https://www.ankitcodinghub.com/product/verilog-lab-3-combinational-circuit-building-blocks-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91441&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Verilog Lab 3-Combinational-Circuit Building Blocks Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 3

Combinational-Circuit Building Blocks

The purpose of this lab is to build useful digital circuits by combining different combinational- circuit building blocks, such as multiplexers, decoders, priority encoders, and seven-segment code converters. In all parts, you will be displaying a numerical output using one of the available seven-segment digits.

Part 1 (Displaying the output of a priority encoder)

In this part, you will explore the functionality of a priority encoder by connecting its inputs to switches and displaying the hex number of the highest asserted switch. The number will be displayed on a single seven-segment digit.

The following steps should guide you through the implementation:

<ol>
<li>Import the priority_encoder_generic.v from the starter code. The moduledescribes a generic priority encoder where the number of inputs is parameterized.</li>
<li>Import the hex2sseg.v from the starer code. The module describes a hexadecimal toseven-segment coder converter.</li>
<li>Design a test system for the priority encoder. The system should use a priority encoderof size 16×4 and a hexadecimal to seven-segment code converter to display its outputon one of the seven-segment digits.</li>
<li>Draw a schematic of the test system and include it with your submission.</li>
<li>Write a verilog module (call it prior_encoder_test.v) that describes the testsystem you designed.</li>
<li>Verify the functionality of the test system by implementing it on the FPGA board usingthe following IO specifications:
<ol>
<li>SW15ßSW0 connected to the 16 inputs of the priority encoder. Assume SW15has the highest priority.</li>
<li>Activate a single seven-segment digit by setting its AN to 0</li>
<li>Connect the output of the hex2sseg code converter to the seven-segmentdisplay LEDs</li>
<li>Turn off the decimal point (DP)</li>
</ol>
</li>
</ol>
Part 2 (Building a rudimentary seven-segment display driver)

The objective in this part is to explore an application of binary decoders and introduce you to a very rudimentary seven-segment display driver. You will also build a test circuit that takes a 3- bit input X and display the value of X on a seven-segment digit. The location of the activated digit will be the same as the value of X. In other words, if X is set to 3’b101, then the seven- segment digit located in the 5th place will be activated and it will display the number 5.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Assuming the very first seven-segment digit location is 0, then changing X from 0 to 7 should activate the digits in order and display the appropriate number on each digit.

The following steps should guide you through the implementation:

<ol>
<li>Import the decoder_generic.v from the starter code. The module describes ageneric decoder where the number of inputs is parameterized.</li>
<li>Import the hex2sseg.v from the starer code. The module describes a hexadecimal toseven-segment coder converter. (If you are using the same project as in Part 1, youshould have this module imported already)</li>
<li>Use the 2 imported modules to design a rudementary seven-segment driver (call itfirst_sseg_driver). The driver should have the following specfications:
<ol>
<li>3-bit input active_digit to select one of eight seven-segment digits toactivate</li>
<li>4-bit input num containing a binary number to be displayed on the activateddigit</li>
<li>1-bit input DP_ctrl to turn on/off of the decimal point</li>
<li>Outputs to set the appropriate seven-segment control signals (i.e. sseg, AN,DP)</li>
</ol>
</li>
<li>Draw a schematic of the driver and include it with your submission.</li>
<li>Design a test system that that utilizes the driver and implements the functionalitydescribed above. In other words, connect a 3-bit input X to both the active_digit and num. (Call this system first_sseg_driver_test). The system should output appropriate seven-segment control signals (i.e. sseg, AN, DP).</li>
<li>Verify the functionality of the test system by implementing it on the FPGA board using the following IO specifications:a. SW2ßSW0 connected to the inputX.

b. Connect the seven-segment control signals to appropriate output from thesystem.</li>
<li>In your video demo, change X from 0 to 7.</li>
</ol>
Question: If you were able to change the input X very quickly, say in the order of 30 times per second or more, what would happen?

Part 3 (Using the rudimentary seven-segment display driver at the output of a simple calculator)

The objective of this part is to use the rudimentary seven-segment display driver to show the result obtained from the modified simple calculator you built in lab2. The digits can only be displayed one at a time using some selector switches. You can assume all numbers are unsigned for this part.

Recall, the calculator should perform 4-bit addition, subtraction, multiplication, and should utilize a binary-to-BCD converter to generate a 3 digit BCD (or 12-bit) result.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol>
<li>Write a verilog module (call it simple_calc_first_sseg) that will contain the whole system for this part.</li>
<li>Import simple_calc along with all necessary dependencies (i.e. the adder/subtractor, csa multiplier,etc.)

As a remindera. The module should accept two 4-bit inputs X, Y

b. The module should accept a 2-bit operator select input (op_sel).i. op_sel = 00 (add)

ii. op_sel = 01 (subtract) iii. op_sel = 1x (multiply)</li>
<li>Import bin2bcd (from lab2) to convert the 8-bit binary output of the calculator to its equivalent 12-bit BCD.</li>
<li>Import mux_4x1_nbit from the starter code. The module describes a generic 4×1 multiplexer where the number of bits for each input is parameterized.</li>
<li>Separate the 12-bit BCD result into 3 BCD digits (4-bit each) and connect each of the digits to one of the inputs of the 4×1 MUX.</li>
<li>Use the first_sseg_driver module to display the 3-digit BCD result on the seven-segment digits (4, 5, 6)</li>
<li>Draw a schematic of the whole system and include it with your submission. You do not need to show the content of the seven-segment driver or the simple calculator, just include them as boxes with inputs and outputs.</li>
<li>Verify the functionality of your simple calculator by implementing in on the FPGA board using the following IO specifications:i. SW3ßSW0 for the inputX ii. SW7 ß SW4 for the input Yiii. SW9 ß SW8 to control which seven-segment digit is activated (these switches will select digits 4, 5, 6, 7)
iv. SW15 ß SW14 for the op_sel

v. Seven-Segment7 ß Seven-Segment4 for the output BCD result

vi. LED14 to display the carry_out of the adder/subtractor vii. LED15 to display the overflow of the adder/subtractor
</li>
</ol>
Submission check list:

[ ] All Verilog code you generated or modified

[ ] All testbenches written

[ ] Embed all screenshot of your testbench output in your README.md [ ] Embed all block diagram generated in your README.md

[ ] 3 Short videos demonstrating each of the parts

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
