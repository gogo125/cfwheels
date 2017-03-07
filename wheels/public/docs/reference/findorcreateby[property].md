```coldfusion
// Return the first object that matches "Timberlake" in the last name column. If there is no match, create a new one and set firstName to "Justin".
newArtist = model("artist").findOrCreateByLastName(lastName="Timberlake", firstName="Justin");
```