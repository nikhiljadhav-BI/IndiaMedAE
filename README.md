# IndiaMedAE
need -
bfc, pva environment
html file, zip file, dialog files, bot response file, three flow files



Frontend



html file, need botid, if we replace botid with other bot, we are good to go



Backend



import zip file in power apps as a solution
Open bot in bfc from pva
open dialog files and bot response file
add dialog in bot (from ... of root bot) give any name
click on dialog of new dialog
click on show code
replace existing code with dialog file code
click on botresponses in left menu
click on new dialog
click on show code
click on dialog interface
go to output
click on add new
set key to selection
set type to string
replace existing code with bot response file
click publish
click on bot
click on publish selected bot
enter credentials for target environment



go back to pva and refresh so you see the new topic created
go to "greeting"
add node after "question", click on redirect to another topic, select bfc topic that we created earlier
go to question and move connection inputs to "redirect" block
delete "question" block



create a flow that is triggered by pva and must send back to pva
create an input for each of the inputs in the flow file(11 inputs for the send email flow)



click add a node
click call action
if the flow does not exist, click create flow(this will take you to power automate)
add a flow, if it is not there, create the flow u
