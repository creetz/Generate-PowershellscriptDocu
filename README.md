![example](https://github.com/creetz/Generate-PowershellscriptDocu/blob/master/pic1.png)

  .SYNOPSIS
  Create PowerShell Script Documentation
   
  Christian Reetz
  (Updated by Christian Reetz to support Exchange Server 2013)
	
	THIS CODE IS MADE AVAILABLE AS IS, WITHOUT WARRANTY OF ANY KIND. THE ENTIRE 
	RISK OF THE USE OR THE RESULTS FROM THE USE OF THIS CODE REMAINS WITH THE USER.
	
	26.02.2016
	
  .DESCRIPTION

  This scripts take the synopsis from powershell files and build a html-based documentation
	
	PARAMETER export
  path to export the html-documentation-file...
	
	EXAMPLES
  .\Generate-PowershellscriptDocu.ps1 -export c:\temp\my-powershell-html-documentation.html
