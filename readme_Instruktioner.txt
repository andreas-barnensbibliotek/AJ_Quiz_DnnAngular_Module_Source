What you need to do step by step:
Create a Folder (example: "Demo-Angular6") inside your DNN /desktopmodule/Demo-Angular6/
Clone this project from git inside /desktopmodule/Demo-Angular6/ (all files should be in root folder)
Open solution (filename.sln) with visual studio 2015
Re-naming the project/solution
Change Assembly name and Namespace
Build your solution and check any error. ( det kan vara så att man måste tabort dotnetnuke och importera den igen från bin. samma gäller system.web.http det är fel versioner från början)
It's time to register Module inside your DNN
Login as host.
Go to host->extension->Create new module
select control module
"folder name"
"Business Controller": [namespace].Controller.BusinessController,[namespace] (ex. AngularNGMD.Controller.BusinessController,AngularNGMD)
insert module name: Demo Angular 6
Add "Module definition"
Add "Module control (folder, source file: index.html, Type: view)"


i angularmodulen i context.service.ts måste man ändra modulnamn så att det är samma som in dnnmodulen