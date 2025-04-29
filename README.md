Usage

Windows:

Invoke-WebRequest -Uri https://raw.githubusercontent.com/crowdstrike/falcon-scripts/v1.8.0/powershell/install/falcon_windows_install.ps1 -OutFile falcon_windows_install.ps1; .\falcon_windows_install.ps1 -FalconClientId XXXXXXX -FalconClientSecret YYYYYYYYY  

Linux:

export FALCON_CLIENT_ID="XXXXXXX"   
export FALCON_CLIENT_SECRET="YYYYYYYYY"   
curl -sL https://raw.githubusercontent.com/crowdstrike/falcon-scripts/v1.7.3/bash/install/falcon-linux-install.sh | bash  
