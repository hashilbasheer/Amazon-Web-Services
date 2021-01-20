### 1) Login to ZENWORKS (AWS Patching tool)

###        ------> Doing CleanUp activity using CleanUp activity tool

#### Checking every servers the patching tool is installed or not( ZENWORKS). If not,Uninstall the Zenwork agent and reinstall it ,Tool might be corrupted ,so have to reinstall by doing the following :-

Run the tool-->UnZip-->UnInstall Zenwork agent -->Give the key,pwd (that given in the mail from client) -->then start (Reboot automatically)

#### Select servers-->OK

### 2) Checking Patching --Only 34 servers showing Zenworks status instead of 36 servers--> Action-->Disable (Disable unnecessary patches)

Service name called- Novell Zenworks Agent Service

Tools
-------

AWS                                                 AZURE

Security tool called
---------------------

TrendMicro Deep Security                          Inbuilt Defender

Monitoring
-----------

ZenOS                                               SCOM

Patching
---------

ZenWorks                                             SCM

Vulnerability Fix
------------------

Qualys                                               Qualys


