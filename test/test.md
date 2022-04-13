# Markdown Test

Use this file to check if syntax highlighting seems to be working correctly.

```cfml
<cfif true>
	<cfset variables.foobar = false />
</cfif>
```

```cfscript
if (true) {
	variables.foobar = false; // comment
}
writeOutput("foobar #variables.foobar#");
queryExecute("SELECT * FROM myTable WHERE myField = ?", [variables.foobar]);
variables.binbaz = new Foobar();
variables.binbaz.myMethod(myarg=variables.foobar);
/**
 * @myArg It's an argument.
 * @return Something?
 */
function myFunction(required boolean myArg) {
	return arguments.myArg;
}
cfmail(from=variables.from, to="example@example.com") {
	writeOutput("foobar");
}
```

```cfscript
component extends="something.something.something.DarkSide" {
	public component function init(required string something, string something, string something, boolean complete = false) {
		return this;
	}
}
```