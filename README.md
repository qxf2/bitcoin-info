# bitcoin-info
A sample Android application created by [Qxf2 Services](https://www.qxf2.com/?utm_source=bitocin-app&utm_medium=click&utm_campaign=From%20Github).


__Setup for Mobile/Appium automation__


a) [Download and Install appium desktop app](https://github.com/appium/appium-desktop/releases/latest)

b) [Download and Install Android Studio and create an emulator](https://developer.android.com/studio/index.html)

c) [Install Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

d) [Install the appium Python client library](https://pypi.python.org/pypi/Appium-Python-Client)
pip install Appium-Python-Client

__If your setup goes well__, you should be to run a simple mobile test with this command after starting the Appium and Android emulator:
`pytest -k mobile_bitcoin_price -H $Emulator_OS_Version -I $Emulator_Name`

__Optional steps__ for more details on setting up appium and running tests on Android or iOS refer to below links:
* [Get started with mobile automation: Appium & Python](https://qxf2.com/blog/appium-mobile-automation/)
* [Get Set Test an iOS app using Appium and Python](https://qxf2.com/blog/get-set-test-an-ios-app-using-appium-and-python/)
