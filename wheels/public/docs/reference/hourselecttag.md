```coldfusion
// This "Tag" version of the function accepts a `name` and `selected` instead of binding to a model object 
<cfoutput>
    #hourSelectTag(name="hourOfMeeting", selected=params.hourOfMeeting)#
</cfoutput>

// Show 12 hours instead of 24 
<cfoutput>
	#hourSelectTag(name="hourOfMeeting", selected=params.hourOfMeeting, twelveHour=true)#
</cfoutput>
```