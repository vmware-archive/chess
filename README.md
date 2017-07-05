# Chess
Tiny client-side javascript chess game based on the program that won an International Obfuscation Code Contest. 

The original author of the code is Oscar Toledo G.

This is an easy to use chess program which you can cf push to CF (Cloud Foundry) without any changes.

# Instructions for beginners
(1) Download index.php and manifest.yml from this repository to a new, empty directory on your PC or Mac

(2) Install the cf cli (Cloud Foundry Command Line Interface) on your machine: https://docs.cloudfoundry.org/cf-cli/install-go-cli.html

(3) If you do not have a CF account, create one at https://run.pivotal.io

(4) Execute the cf api command to point to your CF installation

    e.g. c:\Users\me\projects> cf api api.run.pivotal.io --skip-ssl-validation
    
    n.b. You may not need to use the "--skip-ssl-validation" if your CF installation has the proper SSL Certs in place

(5) Execute the cf login command 
    
    e.g.  c:\Users\me\projects> cf login
    
    n.b.  You may be asked to select an Org and a Space if your administrator gave you access to more than one Org/Space combination

(6) Change to the directory where you downloaded chess.php and manifest.yml

(7) Execute the cf push command to upload the chess.php code, install dependencies, create container, ... (all automatically)

(8) Once the command prompt is returned to you, look for "urls:" line and try it out using a browser on your PC or Mac

