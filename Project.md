<html>
<head> 
<body style="background-color:Black; width=100% margin:100% padding:100%">

<p style="float:left;">
<img src="wtp1.jpg" style="float:left;" class="border" hspace="20">
<p style="font-family:Courier; color:White; font-size: 19px;"> <b> Project Idea </b>
<br>
<p style="font-family:Courier; color:White; font-size: 19px;" <b> Overview </b> </p>
<br>
<p style="font-family:Courier; color:LightGrey; font-size: 14px;"> My project idea would be to streamline equipment maintenance requirements in the water industry by automating the raising of job requests when equipment fails. The concept would utilise the SCADA system operating an asset. Alarms and events of equipment could be classified and defined for which department of maintenance is required to rectify the issues as diagnosed by the system. The command to request maintenance would be automatic and populate the request in the corporate applications where work is scheduled, documented and asset history stored. </p>

<p style="font-family:Courier; color:White; font-size: 19px;" <b> Motivation </b> </p>
<p style="font-family:Courier; color:LightGrey; font-size: 14px;"> Currently this is performed by operators when equipment fails. This is resulting in significant delay between raising requests and the rectification work commencing. This is because part of the process has been streamlined by the industry where works are classified into the fault area. Whether this be electrical, mechanical or control system. However due to varied perception, level of knowledge and experience among operators. The request for an asset to be attended to has the potential to be sent to the incorrect department. Automating this process would work off definitive alarm classification from the equipment behaviours as logged by a SCADA system and remove the variations which delay bringing an asset back online. Operator work efficiency is reliant on scheduled work as opposed to unscheduled. Not only do operators need to raise a work request, but they will need to isolate the equipment for the appropriate maintenance to be carried out, in addition to working alongside maintenance and then de-isolating the equipment in order to bring it back into service. Any delay to the commencement of this process hinders the whole operation. To eradicate the confusion that tends to occur, the SCADA system use may be maximised to automatically raise the work, correctly. </p>       

<p style ="font-family:Courier; color:White; font-size: 19px;" <b> Description </b> </p>
<p <p style="font-family:Courier; color:LightGrey; font-size: 14px;"> Achieving this endeavour would take some significant outlay. It seems a simple concept to export information from one application to another. However the likelihood that the two applications would talk to each other directly is unlikely. There would be a need to assign a collaborative application which would receive the information from the SCADA system, and populate it into the corporate application.
The foundation to base this outcome on would be defining alarms, and equipment behaviours which could be assessed to ensure that when certain alarms are triggered in relationships, they produce a specific outcome of data to be useful in providing specifics to job requests. It may be best to start with what relationships may not require a work request. Such as an
“Instrument off scale” alarm, triggered in close timing with a “Mains Power failed” alarm.
In this instance the reason for the “Instrument off scale” alarm is likely the loss of power to the site. Not a separate problem to the power failure. Where power failures will require either back up power generation, or awaiting providers to re-energise their network.
If however and “Instrument off scale” alarm, is triggered alone, then this behaviour would be classified as an electrical fault at the instrument. Rather than to the site overall. In this case, the alarm and any further detail could be exported automatically from the SCADA system into the connecting application, to then be populated into the corporate planning, asset history and scheduling corporate application. Further, assigned into the electrical department specifically.
It would take a significant period of time to map alarm and event behaviours with faults. However, worthwhile in achieving this seamless reactive maintenance outcomes. The corporate application already has assets assigned identification numbers, so correlating these with points collecting readings from the field into the SCADA would be required as a foundation as well. </p>


<p style ="font-family:Courier; color:White; font-size: 19px;" <b> Tools and Technologies </b> </p>
<p style="font-family:Courier; color:LightGrey; font-size: 14px;"> The software involved to transfer data from one application to another is a resource that would require sourcing. This might be the best option for initial implementation. However a longer term solution may be to determine if there is a SCADA application and a corporate application which would directly communicate with one another. This would be the most effective overall method to ensure some simplicity.>


<p style ="font-family:Courier; color:White; font-size: 19px;" <b> Skills required </b> </p>
<p style="font-family:Courier; color:LightGrey; font-size: 14px;"> The skills required to accomplish this endeavour would be knowledge of the most suitable application to receive and transfer data between the two applications. Also knowledge and experience in both the existing applications to determine their suitability for their continued operation within this new arrangement. Furthermore coding ability within SCADA to export data when certain alarms within relationships have assigned a work request to a particular department will be required.
  
 
<p style ="font-family:Courier; color:White; font-size: 19px;" <b> Outcome </b> </p>
This projects success will be determined by an increased ability to respond to reactive work, correctly. Time to work commencing will be minimised and there will be less impact on scheduled work KPI’s as the reactive works will be planned better with less conversations to try and determine what exactly an operator is requesting in a works request. The instances of multiple work departments allocating lost time and resources as teams are allocated to rectification works when the request has been misdirected will be vastly reduced if not eliminated. Operator resourcing will not be taken from incorrectly due to the back and forth attempts to understand the work required, in addition to confusion surrounding when where and how assets will need to be isolated for the particular team performing the work.







</body>
</html>


