# issa-lab-4--ethernet-solved
**TO GET THIS SOLUTION VISIT:** [ISSA Lab 4- Ethernet Solved](https://www.ankitcodinghub.com/product/issa-laboratory-ethernet-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119100&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISSA Lab 4- Ethernet Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
How the program works

The server starts and the client connects to it. ‘SET DTC’ button sets 4 leds to active/inactive. (ACTIVE = Red, INACTIVE = Green). ‘Set all DTC’ button set all DTC’s active/inactive.

‘SET LED’ button on client side sends a request to the server to set a led color to Green/Red on client GUI.

‘Enter diag mode’ button start the diagnosis mode and ‘Stop diag mode’ stops the diagnosis mode. In diagnosis mode the client can communicate with the server by setting leds on it or read DTC’s status.

In DIAG MODE:

The server can control the DTC’s and the client can READ DTC’s status. The client can set LED states and the server executes client requests.

In Normal mode (DIAG MODE off):

The server still can control the DTC’s but does not communicate with the client

• Exercise 0

Complete in server-gui.py start_server function in order to create a server using method described in previous laboratories.

Complete in client.py start_client function with necessary code in order to connect to the server using the method described in previous laboratories.

• Exercise 1

Complete in client.py, diag function with necessary code in order to send to the server ‘0x3E01’ and set a variable on 1, this means that the diag mode is on.

Complete in client.py, stop_diag function in order to send ‘0x3E00’ and set a variable on 0, this means that the diag mode is off.

Complete in server-gui.py, recv_handler function in order to check if the diag mode is ON/OFF.

• Exercise 2

Complete in server-gui.py, set_dtcX function in order to set the DTC state active/inactive when Set DTC X button is pressed.

Complete in server-gui.py, set_all function in order to set all the DTC state active/inactive when Set all DTC button is pressed.

• Exercise 3

Complete in client.py, get_dtc_state function in order to send, only in diag mode, a hex number ‘0x22XX’ (XX number of dtc – 01 – 04).

Complete in server-gui.py, read_dtcX functions in order to send a message ‘0x62XXYYYYY’ (See the diagram for YYYYY explanation).

• Exercise 4

Complete in client.py, set_ledX_flags function in order to send, only in diag mode, ‘0x2EZZS’ ( See the explanation in the diagram).

Complete server-gui.py, set_ledX, functions in order to send, when in diag mode, the response for ‘0x2EZZS’ and display the state on the leds.

Response for ‘0x2EZZS’ is ‘0x6EZZS’.

Complete in client.py, set_ledX_label function in order to decode the response message and to show the LED state on client Gui.
