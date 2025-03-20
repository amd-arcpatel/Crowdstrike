Usage

To download and run the script directly:

export FALCON_CLIENT_ID="XXXXXXX"
export FALCON_CLIENT_SECRET="YYYYYYYYY"
curl -L https://raw.githubusercontent.com/crowdstrike/falcon-scripts/v1.7.3/bash/install/falcon-linux-install.sh | bash


Alternatively, download the script and run it locally:

export FALCON_CLIENT_ID="XXXXXXX"
export FALCON_CLIENT_SECRET="YYYYYYYYY"
curl -O https://raw.githubusercontent.com/crowdstrike/falcon-scripts/v1.7.3/bash/install/falcon-linux-install.sh
bash falcon-linux-install.sh


Or pass the environment variables directly to the script:

FALCON_CLIENT_ID="XXXXXXX" FALCON_CLIENT_SECRET="YYYYYYYYY" bash falcon-linux-install.sh
