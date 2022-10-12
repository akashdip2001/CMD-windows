# CMD-windows
all important CMD commands in Microsoft Windows

# Creat a Folder
    mkdir "[folder name]"

# Copy
    go to the folder & click the address-bar & wright 'cmd' enter
    Xcopy "AAAAA <space> BBBBB" D:\"Akash 2001" /E/H/C/I 
     
     /E = Copy all sub-folders
     /H = Copy all Hidden folders
     /C = ignore all errors
     /I = confurm all files copy in a particullar folder
     
# Delete a folder
     rd /s /q "C:\Usre\ ... \folder name"
    

# All Save WIFI Passwards // Run cmd in Administrator
    netsh wlan export profile folder=c:\ key=clear
    
# Lock Your Pendrive // Write protected
    diskpart
    list disk
    select disk [1/2/3 ... ]
    attributes disk set readonly
    
    attributes disk clear redonly
    
# Change Color in CMD
    help color
    color 02

# Change the Promt
    help prompt
    prompt akashdip@hacker$G
    
# Change the Title
    title Hacking with Akashdip
    
# Hide Your Personal Stuff
    Attrib +h +s +r [folder name]   // to Hide the filder
    Attrib -h -s -r [folder name]   // Un Hide

# Copy any Output to Clipboard
     ipconfig         // Output
     ipconfig | clip  // all output copy to clipbord
     
# View Command History
     F7 key
     
# Creat Folder with Reserved name
     md aux\
     md con\
     
# View all Installed Programs
     wmic product get name
     
