#TODO for 1.0 
-Migrate to paper-checkbox style - DONE <br/>
-Allow checked already. Need to grab status on attached - DONE <br/>
-Do polyemer standard docs - https://www.polymer-project.org/1.0/docs/tools/reusable-elements <br/>
-More refernces back to ../ from bower_components


#Input
- Expects input to contain array of objects: {"id":"<RETURNED ID>", "name":"<UI NAME>", "selected":<true/false>} in list-values<br/>
- To get checked status, use two way biding to both set and capture values. For example:<br/>
'''<checkbox-multiselect list-values = '{{myValueList}}' display-options = ''></checkbox-multiselect>'''

#Future Release Enhancements
- Add display-options object for additional UI control <br/>
- options: <br/>
-- displayStacking (inline /stacked)<br/>
-- boxColour<br/>
-- animateSelect (true / false)<br/>

#Versioning
### Version 1.0
Coming soon!
