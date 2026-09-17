## Onboarding for lab members

### Table of Contents  
1. **Lab resources**  
   a. Fill out your availability each semester: [Fall 2026](https://whenisgood.net/t5mq7r2)  
   b. Complete the [Lab Starter form](https://docs.google.com/forms/d/e/1FAIpQLSf_oR79KD-z1hIAYfJDysNim1lEU1svzSYCwfcd41kZI3bq7A/viewform?usp=sharing&ouid=109973772250957409002)  
2. **Training**  
   a. [General lab](#training-general-lab)  
   b. [Live animals](#training-live-animals)
3. **Information Technology (IT)**  
   a. [Connecting to a printer](#it-connecting-to-a-printer)  
   b. [Connecting to the lab server](#it-connecting-to-the-lab-server)  
   c. [Mapping the lab server to your computer](#it-mapping-the-lab-server-to-your-computer)  
   d. [How to create Google-like docs with Synology](#it-how-to-create-google-like-docs-with-synology)  
<br>

---
### Training
#### Training: General Lab
Before working in the research lab, you must complete the following training modules and then email Dr. Kawano when you are done. Additional training modules may be required depending on your research project. 
1. [Chemical Safety and Waste Training for Research Personnel & Students](https://researchcompliance.web.virginia.edu/training_html5/home.cfm?navigationKey=O4.KOPWTZDFDT)
2. [Chemical Safety - Formaldehyde Awareness](https://researchcompliance.web.virginia.edu/training_html5/home.cfm?navigationKey=K693.4.74K9ANEWV234PUFNA) 
3. [Chemical Safety - Chemical Storage: A General Guideline](https://researchcompliance.web.virginia.edu/training_html5/home.cfm?navigationKey=R91332145676.0.2802)
4. [Fire Safety - Fire Safety in Labs, Shops, & Studios](https://researchcompliance.web.virginia.edu/training_html5/home.cfm?navigationKey=V9.AD56NFGE45)
5. [PPE - Eye Protection](https://researchcompliance.web.virginia.edu/training_html5/module_content/071/index.cfm)
6. [PPE - Glove Selection](https://researchcompliance.web.virginia.edu/training_html5/home.cfm?navigationKey=R43.0.99209)

Click [HERE](https://researchcompliance.web.virginia.edu/oehs/management_training/read_only/data/search_training_records.cfm) to check your training records.

[▲ Back to Top](#table-of-contents)  
<br>  

#### Training: live animals
If you will be working with live vertebrate animals, you must also be an approved animal handler on Dr. Kawano's animal care and use protocol at the Unviersity of Virginia (UVA). You are NOT permitted to enter the animal facility until you receive confirmation that you are an approved animal handler from UVA's Animal Care and Use Committee (ACUC) _and_ you complete in-person training sessions with Dr. Kawano. 
1. Refer to "[Becoming an animal handler](https://compliance.research.virginia.edu/about/training/animal-research-training)" for the general overview of the training requirements.
2. Access the online [Animal Handler Access Portal](https://compliance.research.virginia.edu/about/training/animal-research/animal-research-online-training)
3. At the top of your Animal Handler profile, click on "Training Records & Facilities"
4. Complete the modules listed under "MUST COMPLETE the following training modules", which should include:
   -  Animal Research - UVA Working Safely with Animals
   -  Animal Research - UVA Orientation Seminar
   -  Animal Research - AALAS-ALL UVA-Orientation to the Animal Care and Use Program
   -  Animal Research - AALAS-ALL UVA Refresher for Animal Handlers
   -  Animal Research - AALAS-ALL UVA Introduction to Wildlife
   -  Animal Research - AALAS-ALL Introduction to Fish
   -  Animal Research - AALAS-ALL Introduction to Amphibians
6. Complete your RRMHA - Research Related Medical Health Assessment. Answers to the following questions about the work environment are:
    -  Question: Are you listed on an IACUC protocol as an Animal Handler? Answer: YES
    -  Question: Are you potentially exposed to BSL 3 or higher agents? Answer: NO
    -  Question: Are you listed on an IACUC protocol as a handler of Non-Human Primates? Answer: NO
    -  Question: Do you require annual respirator training/fit testing? Answer: NO
    -  Question: Are you listed on a Center for Comparative Medicine Health Program IACUC protocol? Answer: NO
    -  Most personnel click on _"I will complete UVA's web-based Medical Questionnaire (designed to assess risk and major health changes) in order to attempt completion of my Health Assessment electronically online."_ However, you should check in with your General Physician to assess whether they would recommend a face-to-face (in-person) health assessment with UVA's Health Care Professional, especially if you have one or more underlying medication conditions that could be affected by working with live vertebrate animals.
7. You will receive an email from the UVA ACUC once your Animal Handler documentation has been completed. Please email Dr. Kawano to schedule a time to complete the in-person, lab-specific animal care training for our lab.

Click [HERE](https://researchcompliance.web.virginia.edu/oehs/management_training/read_only/data/search_training_records.cfm) to check your training records.  

[▲ Back to Top](#table-of-contents)
<br>  
  
### Information technology (IT)
#### IT: Connecting to a printer
1. Follow the instructions for [Macs](https://support.apple.com/guide/mac-help/connect-a-printer-to-your-mac-mh14004/mac) or [PCs](https://sscs.uchicago.edu/add-network-printer-windows10/)
2. Type in the IP address for the printer (e.g.,  172.28.201.64 for HP Color Laser Jet Enterprise MFP M480 in the Wilbur computer lab)  
  
[▲ Back to Top](#table-of-contents)
<br>  

#### IT: Connecting to the lab server
We save our lab files in two formats: physically on a hard drive and electronically on an online cloud platform (i.e., Synology). After Dr. Kawano sends your account information, you can log into the lab server by navigating to [https://finsandlimbs.us1.quickconnect.to/](https://finsandlimbs.us1.quickconnect.to/).  
**Important** Materials on our lab server CANNOT shared with others, unless you receive written consent from Dr. Kawano (and/or the lab member if the materials are saved under their individual folder).   

[▲ Back to Top](#table-of-contents)
<br>  

#### IT: Mapping the lab server to your computer
Connecting to the lab server through a web browser is convenient when you want to upload/download a few files, but most times it's more useful to map the server as a network drive on your personal computer. 
1. Download [OpenVPN](https://openvpn.net/client/)
2. Download the [Tiktaalik_VPNConfig.ovpn] file from our lab server (Research_LabFiles --> _labDocs), and save to your computer
3. Double-check the Tiktaalik_VPNConfig.ovpn file saved onto your computer, and click "Import" to confirm importing the profile into OpenVPN
4. Click connect, and then type in the username and password that you created when logging onto the lab server through your web browser
5. A window will pop up saying "Missing external certificate". Click on the button "Add Certificate", and then click on the dial next to "Require External Certificate" so the icon changes from mostly blue with white circle to mostly white with blue circle. Click Save Changes.
6. On the left hand side, click on the icon with three horizontal lines and then click on Settings.
7. Click on Launch Preferences, and then make sure that "Launch at Startup" is turned off (click on the icon so it becomes mostly white with a blue circle on the left). This prevents OpenVPN from logging onto the server whenever your computer is on.
8. **Apple (MacOS) users**  
    - Start with the instructions under  "Access your storage system from a Mac computer" on the following link: [https://kb.synology.com/en-br/DSM/tutorial/access_nas_from_mac](https://kb.synology.com/en-br/DSM/tutorial/access_nas_from_mac)
   - The SMB path is SMB://10.8.0.1/Research_LabFiles
   - Enter the username and password that was assigned to you in a separate email from Dr. Kawano
9. **PC (Windows) users**  
    - Follow the instructions on [https://kb.netgear.com/19864/How-do-I-map-a-network-drive-in-Windows](https://kb.netgear.com/19864/How-do-I-map-a-network-drive-in-Windows).
    - The path to the shared network folder is \\10.8.0.1\Research_LabFiles
    - Enter the username and password that was assigned to you in a separate email from Dr. Kawano.  
 
[▲ Back to Top](#table-of-contents)
<br>  

#### IT: How to create Google-like docs with Synology
Missing Google Docs / Slides / Spreadsheet? Synology doesn't directly connect to Google Drive, but we can create similar documents through Synology Office.
Instructions provided by Google AI Overview and [https://www.youtube.com/watch?v=QTInhv8esXs](https://www.youtube.com/watch?v=QTInhv8esXs).
1. Log into the lab server.
2. Open the Package Center.    
3. Search for and install Synology Drive Server (which contains the web interface).  
4. Install Synology Office from the Package Center to access web-based document, spreadsheet, and slide editors.
6. Open the Synology Drive app by clicking on the Main Menu (the grid icon on the top-left corner of the browser).
7. Navigate to the folder where you want to create a new document. 
8. Click the + Create button, and select Document to start typing and collaborating securely through our lab server.  

[▲ Back to Top](#table-of-contents)
<br>  
