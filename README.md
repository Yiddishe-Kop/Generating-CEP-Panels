# Generating-CEP-Panels
Info on ZXPSignCmd


1. Create a certificate:

`./ZXPSignCmd -selfSignedCert IT BO Newgraph "Yehuda Neufeld" 12345678 cert.p12`



2. Sign & generate .zxp installer:

`./ZXPSignCmd -sign ../ZXP\ file com.beitalef.fontsPanel.zxp cert.p12 12345678 -tsa http://timestamp.globalsign.com/scripts/timstamp.dll`

ZXPSignCmd -sign inputDir outputZxp p12 p12Password [options]

ALL DONE!
