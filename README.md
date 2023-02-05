# GetNHSE

A project/website that originally (and still does, by default) uses Azure API REST requests to grab the latest Pipeline build of [NHSE](https://github.com/kwsch/NHSE) but can be used for any Azure Pipeline.

You may use this by simply adding your own parameters to the URL.

The following parameters are required:

`org`: Your Azure organization.

`proj`: Your Azure project name.

`projurl`: Wherever your source is located.

For example, 

[https://Bakakaito.github.io/GetMBDM/?org=project-pokemon&proj=pkNX&projurl=https://github.com/kwsch/pkNX](https://Bakakaito.github.io/GetSBMB/?org=project-pokemon&proj=pkNX&projurl=https://github.com/kwsch/pkNX)

will get you the latest Azure Pipeline build for pkNX, and will redirect users directly to the Pipeline/source if anything is going wrong.

CSS very graciously provided by [MirayXS](https://github.com/MirayXS)

Enjoy!
