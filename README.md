# Custom CSS for Visual Studio Markdown PDF 

1. In Settings --> markdown-pdf, find "Markdown-pdf: Styles" and click on "Edit in settings.json".  

2. settings.json is located in %APPDATA%\Roaming\Code\User in Windows, so save the file markdown-pdf.css in the same location. 

3. Add the path to the CSS file as follow (Replace %APPDATA% with your current AppData folder path):

```json
{
    "markdown-pdf.styles": [
        "%APPDATA%\\Roaming\\Code\\User\\markdown-pdf.css"
    ]
}
```  
4. Save and export to PDF. A PDF file with the style defined in markdown-pdf.css will be generated.