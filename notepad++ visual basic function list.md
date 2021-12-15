## Visual Basic function list on Notepad++

In order to make Function List work for your language (if not supported), you should modify (or add) the vb.xml file of the languge. The XML files for different languages can be found in %APPDATA%\notepad++\functionList or in the functionList folder located in Notepad++ installation directory if you use the portable (zip) package.

Tested in Notepad++ version 7 and 8.

copy this following code and save as vb.xml file:
```
<?xml version="1.0" encoding="UTF-8" ?>
<NotepadPlus>
	<functionList>
		<!-- ========================================================= [ VB ] -->
		<parser
			id         ="vb_function"
			displayName="Visual Basic (.NET|Script|for Applications)"
			commentExpr="(?m:((?&lt;=&apos;).*?$)|((?i:REM)([\t ].*?)?$))">
			<classRange
				mainExpr="(?s:(?&lt;SCOPE&gt;(?i:CLASS|TYPE)).*?(?i:END[\t ]\k&lt;SCOPE&gt;))"
				displayMode="node" >
				<className>
					<nameExpr expr="(?i:CLASS|TYPE)[\t ]+(?:[A-Za-z_][\w]*\b)(?:.*?[\r\n])" />
					<nameExpr expr="[\t ]+(?:[A-Za-z_][\w]*\b)" />
					<nameExpr expr="[A-Za-z_][\w]*" />
				</className>
				<function
					mainExpr="(?m:^[\t ]*(?i:(?:(?:PUBLIC|PRIVATE|PROTECTED|FRIEND|PROTECTED FRIEND)[\t ]+)?(?:(?:STATIC|SHARED|SHADOWS|OVERRIDABLE|OVERRIDES|READONLY|WRITEONLY)[\t ]+)?(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$))" >
					<functionName>
						<funcNameExpr expr="(?i:(?:(?:PUBLIC|PRIVATE|PROTECTED|FRIEND|PROTECTED FRIEND)[\t ]+)?(?:STATIC[\t ]+)?(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$)"/>
						<funcNameExpr expr="(?i:(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$)"/>
						<funcNameExpr expr="(?i:(?:GET|LET|SET)[\t ]+)?[A-Za-z_][\w]*(?=[\t ]*\(|$)"/>
					</functionName>
				</function>
			</classRange>
			<function
				mainExpr="^[\t ]*(?i:(?:(?:PUBLIC|PRIVATE|PROTECTED|FRIEND|PROTECTED FRIEND)[\t ]+)?(?:(?:STATIC|(?:DECLARE(?:[\t ]+(?:ANSI|UNICODE|AUTO))?))[\t ]+)?(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$)"
				displayMode="$functionName">
				<functionName>
					<nameExpr expr="(?i:(?:(?:PUBLIC|PRIVATE|PROTECTED|FRIEND|PROTECTED FRIEND)[\t ]+)?(?:(?:STATIC|(?:DECLARE(?:[\t ]+(?:ANSI|UNICODE|AUTO))?))[\t ]+)?(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$)"/>
					<nameExpr expr="(?i:(?:SUB|FUNCTION|PROPERTY)).*?(?:\(|$)"/>
					<nameExpr expr="(?i:(?:GET|LET|SET)[\t ]+)?[A-Za-z_][\w]*(?i:[\t ]+(LIB|ALIAS)[\t ]+[\w&quot;\.]+)*(?=[\t ]*\(|$)"/>
				</functionName>
			</function>
		</parser>
	</functionList>
</NotepadPlus>
```
