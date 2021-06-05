# DocFx
DocFX is an API documentation generator for .NET, which currently supports C#, VB and F#. It generates API reference documentation from triple-slash comments in your source code.

- DocFx: https://dotnet.github.io/docfx/tutorial/walkthrough/walkthrough_create_a_docfx_project.html
- XML documentation comments: https://docs.microsoft.com/en-us/dotnet/csharp/codedoc

#### *Note: this is just a sample project as a reference*

___


#### Tools:
- Visual Studio 2019

#### Steps:
1. Open the project "DocFx" with Visual Studio 2019
2. Locate the **docfx.exe** (packages\docfx.console.2.57.2\tools\docfx.exe) & **\_site** folder (DocFx\\_site)
3. Open command prompt and run the command to serve `docfx serve docfx_project/_site`  
    
    E.g. `C:\Git\DocFx\DocFx\packages\docfx.console.2.57.2\tools\docfx.exe serve C:\Git\DocFx\DocFx\DocFx\_site`
    ![Command Prompt](https://raw.githubusercontent.com/616jk/DocFx/main/screenshot_cmd.png)
    
4. Website successfully run at http://localhost:8080    
    ![Website](https://raw.githubusercontent.com/616jk/DocFx/main/screenshot_website.png)

5. Modify the XML documentation comments (https://docs.microsoft.com/en-us/dotnet/csharp/codedoc), build the project and refresh the webpage (http://localhost:8080) to see the changes.


#### Youtube: 
visual studio 2019 c# DocFx
https://youtu.be/ePZakZnBSEE

#### Screenshot:

![Website](https://raw.githubusercontent.com/616jk/DocFx/main/screenshot_website.png)
