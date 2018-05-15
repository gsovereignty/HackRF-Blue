##  HackRF Blue
http://hackrfblue.com
![https://github.com/gazhayes/HackRF-Blue/blob/master/Screen%20Shot%202018-05-15%20at%201.55.55%20PM.png?raw=true](https://www.indiegogo.com/projects/hackrf-blue#/)
The HackRF Blue is a 0-6GHz software defined radio for RF research projects. It was funded through [Indiegogo](https://www.indiegogo.com/projects/hackrf-blue#/).

This github repo aims to reduce the cost and increase access to full-featured SDR.

My aim is to update this project with <b>everything</b> you need in order to manufacture the HackRF - what better way to reduce prices than fostering competition. Of course, you can work all this out from the HackRF One project itself, but you'll need to go through the process of manufacturing to get the information you need. I've gone through that process and by putting my experience here I hope to save you some time, effort, and expense. I've also educated the manufacturer (which I imagine would have been far more difficult without speaking Chinese) and you can also leverage off that if you use the same one.

In the BOM you will find notes about individual parts. Some parts can safely be replaced with Chinese parts, others cannot. 

<h3>When costing the project, keep in mind the following:</h3>
<p>1. There will be a certain percentage of boards that will not work (or not work well) after manufacturing, in our case the number was 30% which would normally be stupidly high, but not for something like the HackRF. About 3% will not power up at all, another 3% will not enter DFU mode. These are 'traditional' manufacturing problems and can be easily fixed. With the HackRF though, about 20-25% will have poor RF performance due to a range of sometimes very weird issues (hint: mix in a little bit of good quality flux with the solder paste, after doing this things improved a lot). Boards with problems will need to be reworked by hand. You cannot rely on factory staff to be able to diagnose and rework something like poor RF performance unless you use a very experienced (and expensive) manufacturer. In our case, I reworked these boards myself and educated the factory staff during the process. If you are lucky, this experience will help reduce your costs, but expect at least 10% of the boards to require reworking by yourself or an RF engineer.</p>
<p>2. The BOM here does not include headers, SMA connectors, or RF shielding. These should be costed sepairately as different people want different combinations.</p>
<p>3. It is very inadvisable to embark on a manufacturing project as complicated as the HackRF if you haven't built a board yourself because when you have a factory full of staff and limited time on the SMT machine you need to be able to think fast and solve any problems very quickly under considerable pressure, in other words you need to have an intimate understanding of how the HackRF works.</p>
<p>4. It is very important that you factor the MSL level of various parts into the manufacturing process. For example if you open MSL3 parts to produce a sample board, and those parts are in tape, you can't use them for production a week later.</p>
<p>5. Don't mount the headers or RF shielding before testing. If things need to be reworked they will get in the way. Test the boards, then add these parts after, then test again.</p>

If you would like some PCBs to build your own board, contact me (garethhayes.net). I have a limited number left, if I think you might be able to pull off a manufacturing run I'll give you some.
