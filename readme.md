#checkbox-multiselect
This polymer component allows for an array of objects and selected status to be passed, and an array of checkboxes returned.
The object you pass the values in is updated by the component to refect each boxes checked status. Use two-way binding to extract
selected attribute for each value

#Input
- Expects input to contain array of objects: {\"id\":\"<RECORD ID>\", \"name\":\"<DISPLAYNAME>\", \"selected\":true/false} in list-values<br/>
- To get checked status, use two way biding to both set and capture values. For example:<br/>
<checkbox-multiselect list-values = '{{myValueList}}' display-options = ''></checkbox-multiselect>

#Future Release Enhancements
- Add display-options object for additional UI control <br/>
- options: <br/>
-- displayStacking (inline /stacked)<br/>
-- boxColour<br/>
-- animateSelect (true / false)<br/>

#Versioning
### Version 1.0
Coming soon!
