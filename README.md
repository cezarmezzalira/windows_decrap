# Window\$s 10 Decrap Services\*\*

# How to use:

### DISCLAIMER: Next, the list of Services that you'll disable if you execute all commands:

**DiagTrack**- Connected User Experiences and Telemetry;

**MapsBroker** - Downloaded Maps Broker;

**SEMgrSvc** - Payments and NFC/SE Manager

**autotimesvc** - Cellular Time

**WbioSrvc** - Windows Biometric Service

**lfsvc** - Geolocation Service

**TabletInputService** - Touch Keyboard and Handwriting Panel Service

**PhoneSvc** - Phone Service

**SysMain** - SysMain Service Defaults

**DusmSvc** - Data Usage

# This commands will disable some useful services, please be careful:

**1. Copy only the commands refer to services you want to disable:**

    Set-Service DiagTrack -StartupType Disable
    Set-Service MapsBroker -StartupType Disable
    Set-Service SEMgrSvc -StartupType Disable
    Set-Service autotimesvc -StartupType Disable
    Set-Service WbioSrvc -StartupType Disable
    Set-Service lfsvc -StartupType Disable
    Set-Service TabletInputService -StartupType Disable
    Set-Service PhoneSvc -StartupType Disable
    Set-Service SysMain -StartupType Disable
    Set-Service DusmSvc -StartupType Disable

**2. Click with right button on Start and click on Windows PowerShell(As Admin)**

**3. Click on Yes button at UAC message**

**4. Click with right button inside PowerShell window**

**5. Restart Windows**

### WARNING: If everything is going wrong, replace the word `Disable`, for the word `Enable`, and run the commands again.
