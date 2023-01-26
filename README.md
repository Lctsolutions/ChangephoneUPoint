

Lctsolutions
translate to english
/

ChangephoneUPoint

Public

forked from tianfei15473/ChangephoneUPoint

Cannot fork because you own this repository and are not a member of any organizations.

Code

Pull requests

Actions

Projects

Wiki

Security

Insights

Settings

Lctsolutions/ChangephoneUPoint

This branch is up to date with tianfei15473/ChangephoneUPoint:master.

Latest commit

@tianfei15473

tianfei15473 Update README.md

…

on Jun 26, 2019

Git stats

 6

Files

Type

Name

Latest commit message

Commit time

.settings

The first version

4 years ago

assets

The first version

4 years ago

bin

The first version

4 years ago

gen/com/unking/xposedpoint

The first version

4 years ago

lib

The first version

4 years ago

res

The first version

4 years ago

src/com/unking/xposedpoint

The first version

4 years ago

.classpath

The first version

4 years ago

.project

The first version

4 years ago

.project.bak

The first version

4 years ago

AndroidManifest.xml

The first version

4 years ago

README.md

Update README.md

3 years ago

VIVO.png

change at will

4 years ago

meizu.png

change at will

4 years ago

oppo.png

change at will

4 years ago

project.properties

The first version

4 years ago

README.md

The machine itself is a ZTE V5s mobile phone

See if I can change the phone model manufacturer at will

Now for the item at U point, click the Baidu button to change it to any model of mobile phone, and click Huawei, oppo, and vivo to change it to the corresponding mobile phone model.

wantwantwant

The name of this software is U Dot, what functions can it achieve?

You can modify the mobile phone model, manufacturer, IMEI, screen width and height, IP, connected WIFI name, etc., as long as you think of it

How?

Of course, use the very powerful Xposed framework, which can intercept any method you want to modify

Main implementation code

com.unking.xposedpoint.xposed.XposedManager

Explain how to use the installation to change the project

To download the corresponding configuration file, please go to my Baidu network disk download link: https://pan.baidu.com/s/1pyQOWu9SNmgB7WG4uLHJHA Extraction code: yf50

Prepare a ZTE V5s mobile phone, and ROOT, if there is no ROOT, please go to the software market to download a [360 super ROOT] or [kingroot] in 10 seconds to get root

Install the xposed.installer.apk in Baidu Netdisk to the mobile phone. After the installation is complete, open Xposed Installer-->click the frame-->click Install/Update, and then follow the prompts to restart the phone

Copy the point folder in the Baidu network disk to the root directory of the phone SD card

Install the UPoint.apk in Baidu Network or the UPoint project packaged through the source code to the mobile phone, open Xposed Installer, click on the module, and you will see UPoint in it, check it and restart the phone

The mobile phone restarts successfully, open the U point, and you can switch the mobile phone model at will [Note: The first time you click to install and switch, you may be stuck, please wait, the data is being loaded at this time]

If you want to verify whether the phone model has been switched successfully, you can install [View Phone Information.apk] in the Baidu network disk on the phone, click to open and view
