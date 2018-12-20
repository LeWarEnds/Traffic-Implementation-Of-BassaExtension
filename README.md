These are attempted by my `site_traffic` function within my router's reach and no VPN or similar items were used in this process. The program here is Fiddler as per python requirements

# Getting Started.

Import the following files in the directory of the java file(if you are working on) which will be used to calculate the traffic of the route. For python file, it will be updated when Fiddler will be started using the location of the file.

```
import System;
import System.Windows.Forms;
import Fiddler;
```

#### For the first time the cache will be shown as:

`Pragma: no-cache`

# Fetching Traffic.

While using the python file with fiddler, Approximate amount of traffic is captured. I have used `www.google.com` as an example. So, while getting the process following details are captured.

![](https://user-images.githubusercontent.com/35108041/50298607-893b7180-04a5-11e9-958d-a57962a07995.PNG)

# 📁 Code Data Storage Option.

Also, navigating to one of the websites after getting the data about traffic, that whole data code is stored on this [website](http://www.googletagmanager.com//gtm.js?id=GTM-B76Z) (only for this case)

> This link is used as an example of a particular case which was released while getting the traffic details.

# 🎲 Report Representation.

These are the report for the single packet received after the traffic check.

`# | Result | Protocol | Host | URL | Body | Caching | Content-Type | Process | Comments | Custom
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
6 | 200 | HTTP | prourl.itsecure.co.in:8080 | /URLCategorizerService/URLCategorize | 235 |   |   | emlproxy:4656 |  `|  

> These tables are generated in the software itself and in representative form.

# ❌ Error File Representation. 

Also, when there is an error while capturing the data about traffic, these are the results in the statistics box.

![](https://user-images.githubusercontent.com/35108041/50288343-af541800-048b-11e9-9018-92599f03b663.PNG)

> These errors will not be saved the directory of the file but will be in the logs for temporary time and will be run until the process in running.

![](https://user-images.githubusercontent.com/35108041/50300177-9d816d80-04a9-11e9-8c27-6417af7292cb.PNG)

# Main Credits.

This project and idea mainly belongs to @rohancl(Rohan Singh) for the SCoRe Lab. This is the basic implementation of the process which can be used to make some real applications for the Traffic Calculation of the Route. Also, all mentors are welcome here and all the suggestions will be appreciated.



