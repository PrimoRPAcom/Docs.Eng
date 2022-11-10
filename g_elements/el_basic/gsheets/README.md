# Google Sheets

&#x20;In order to connect to Google Sheets services you need to complete following steps:

Navigate to developer console [https://console.developers.google.com/flows/enableapi?apiid=sheets.googleapis.com](https://console.developers.google.com/flows/enableapi?apiid=sheets.googleapis.com)

Create new project or choose existing then press Continue

![](<../../../.gitbook/assets/image (128).png>)

Press Go to credentials

![](<../../../.gitbook/assets/image (293).png>)

Press Cancel

![](<../../../.gitbook/assets/image (261).png>)

Proceed to OAuth consent screen menu

![](<../../../.gitbook/assets/image (195).png>)

Choose user type and press Create

![](<../../../.gitbook/assets/image (133).png>)

Enter application name (any), user support email address and developer email then press Save and continue on all following forms

![](<../../../.gitbook/assets/image (138).png>)

Navigate to Credentials menu then press Create credentials button. Click OAuth client ID

![](<../../../.gitbook/assets/image (248).png>)

Choose Desktop app and enter application name (any). Press Create button. Securely store information from pop up window (**Your client ID** and **Your client secret**). Press OK

![](<../../../.gitbook/assets/image (198).png>)

Download json file by pressing the button at application row. You will need to enter full local path to this file in property **File path** of **Google Sheets document** element.

![](<../../../.gitbook/assets/image (257).png>)

To work with table you will need it's ID. You can get ID from table URL - it is the alphanumerical string between d/ and /edit parts. Enter that ID into **Spreadsheet ID** property of **Google Sheets document** element.

![](<../../../.gitbook/assets/image (142).png>)
