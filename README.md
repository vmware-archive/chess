# chess
Tiny client-side javascript chess game based on the program that won an International Obfuscation Code Contest. 
The original author of the code is Oscar Toledo G.
An easy to use chess program which you can cf push to CF (Cloud Foundry) without any changes.
(5) Execute the cf login command 
    e.g.  c:\Users\me\projects> cf login
    n.b.  You may be asked to select an Org and a Space if your administrator gave you access to more than one Org/Space combination
(6) Change to the directory where you downloaded chess.php and manifest.yml
(7) Execute the cf push command to upload the chess.php code, install dependencies, create container, ... (all automatically)
(8) Once the command prompt is returned to you, look for "urls:" line and try it out using a browser on your PC or Mac
