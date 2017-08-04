# COM-Object-hijacking
use COM Object hijacking to maintain persistence

This script allows you to use COM Object hijacking to maintain persistence.

Learn from:https://www.gdatasoftware.com/blog/2014/10/23941-com-object-hijacking-the-discreet-way-of-persistence

Code by: 3gstudent@3gstudent

License: BSD 3-Clause

Support x86 and x64 system.

Redefined CAccPropServicesClass and MMDeviceEnumerator.

These two instances are used by a lot of applications, for example by the browser (by using the CoCreateInstance() function). 

When you start iexplore.exe,it also starts calc.exe.

:)
