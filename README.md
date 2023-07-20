# MyCodeSnippets
visual studio code snippets

# Location
```
C:\Users\{USER}\Documents\{Visual Studio 2022}\Code Snippets\Visual C#\My Code Snippets
```
# Example
```
<?xml version="1.0" encoding="utf-8"?>
<CodeSnippets xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">
	<CodeSnippet Format="1.0.0">
		<Header>
			<Title>MyCodeSnippet</Title>
			<Author>MyAuthor</Author>
			<Description>MyDescription</Description>
			<Shortcut>MyShortcut</Shortcut>
		</Header>
		<Snippet>
			<Code Language="CSharp">
				<![CDATA[
string mySnippet = "$MyID$";
]]>
			</Code>
			<Imports>
				<Import>
					<Namespace>MyNamespace</Namespace>
				</Import>
			</Imports>
			<Declarations>
				<Literal>
					<ID>MyID</ID>
					<ToolTip>MyToolTip</ToolTip>
					<Default>MyDefault</Default>
				</Literal>
			</Declarations>
		</Snippet>
	</CodeSnippet>
</CodeSnippets>
```
