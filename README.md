MIDI In/Out/Thru For stuff
========================================

NOTE: work in progress, this should work but still unetched ...  
NOTE2: SF has V_1.2 [[0]](https://github.com/sparkfun/MIDI_Breakout/tree/V_1.2) branch (work in progress) with an added line driver [[1]](http://www.nxp.com/documents/data_sheet/74AHC_AHCT1G125.pdf) for MIDI_OUT and MIDI_THRU.    
common lore on the internet tells its unesscery, midi can survivie hundered of meters without [[2]](https://groups.google.com/forum/#!topic/theatre-sound-list/aL6dRYNXyxQ) [[3](http://www.richmondsounddesign.com/faq.html#midilen).  


SF design suffers from a few problems, like   
* the PROG/RUN jumper : non here, connect your micro to software serial. or whatever  
* the uno formfactor: we are over(under) it, design is for ruggedness  
* 0402 footprint - no need for the tiniest parts. we use thru hole a lot here beaucse anyways the midi sockets are big.  
  
this is a fork, you know  

![](http://i.imgur.com/5HhzLMo.jpg)

![](http://i.imgur.com/By1tSEV.jpg)

