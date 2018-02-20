# Analyser

 
## How can I get the Type of a symbol?

## How to determine the return type of a method?

## What is the difference between a VariableDeclaration and a VariableDeclarator?

## How to get the full namespace of a type or namespace?
 
## What are the different properties of a Diagnostic for?
* Id- wird zum diabled benutzt
* Title
* Message
* Description

 
# CodeFixes

## How to change the return type of a method?

 

# Testing 

How to test Analyzers?
How to test CodeFixes?
How to write Test that include types from thrid party content?


# Nice To Know

SolutionWide Analysis erfassen nur den Teil, welcher zu diesem Zeitpunkt geladen ist. Auch wenn

im Anschluss weitere Projekte geladen werden, werden die Diagnistiken nicht aktualisiert.

# References

https://github.com/DotNetAnalyzers
https://github.com/DotNetAnalyzers/PublicApiAnalyzer
https://msdn.microsoft.com/en-us/library/dd264996.aspx
https://github.com/DustinCampbell/RoslynNUnitLight
https://github.com/nunit/nunit.analyzers
https://github.com/wachulski/nunit-migrator
http://www.alteridem.net/2016/11/11/debugging-visual-studio-extensions/