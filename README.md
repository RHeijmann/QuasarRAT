# QuasarRAT, Modified by Rik Heijmann for educational purposes.
Currently there are no differences since this project has been forked of the project (quasar/QuasarRAT) on 26-12-2018.
Planned changes:
- Better explainations for each line of code.
- Transition from the Windows Forms framework (https://docs.microsoft.com/en-us/dotnet/framework/winforms/) to the Xamarin framework (https://visualstudio.microsoft.com/xamarin/):
    - This allows the possibility for the "Server"-application to be ran on mobile (Android and iOS) devices and on Mac OS.
    - This allow us to theme QuasarRAT for a more professional look.
    
Please note: Time is on my side, I'm not obliged to add functions or to give a release date.
    
**Free, Open-Source Remote Administration Tool for Windows**

Quasar is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

## Features
* TCP network stream (IPv4 & IPv6 support)
* Fast network serialization (Protocol Buffers)
* Compressed (QuickLZ) & Encrypted (TLS) communication
* Multi-Threaded
* UPnP Support
* No-Ip.com Support
* Visit Website (hidden & visible)
* Show Messagebox
* Task Manager
* File Manager
* Startup Manager
* Remote Desktop
* Remote Shell
* Download & Execute
* Upload & Execute
* System Information
* Computer Commands (Restart, Shutdown, Standby)
* Keylogger (Unicode Support)
* Reverse Proxy (SOCKS5)
* Password Recovery (Common Browsers and FTP Clients)
* Registry Editor

## Supported runtimes and operating systems
* .NET Framework 4.0 Client Profile or higher ([Download](https://www.microsoft.com/en-us/download/details.aspx?id=24872))
* Supported operating systems (32- and 64-bit)
  * Windows XP SP3
  * Windows Server 2003
  * Windows Vista
  * Windows Server 2008
  * Windows 7
  * Windows Server 2012
  * Windows 8/8.1
  * Windows 10

## Compiling
Open the project in Visual Studio 2017+ and [restore the NuGET packages](https://docs.microsoft.com/en-us/nuget/consume-packages/package-restore). Once all packages are installed the project can be compiled as usual by clicking `Build` on the top or by pressing `F6`. See below which build configuration to choose from.

## Building a client
| Build configuration         | Usage scenario | Description
| ----------------------------|----------------|--------------
| Debug configuration         | Testing        | The pre-defined [Settings.cs](/Quasar.Client/Config/Settings.cs) will be used, so edit this file before compiling the client. You can execute the client directly with the specified settings.
| Release configuration       | Live use       | Start `Quasar.exe` and use the client builder.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md)

## Roadmap
See [ROADMAP.md](ROADMAP.md)

## License
Quasar is distributed under the MIT License.  
Third-party licenses are located [here](Licenses).

## Thank you!
I really appreciate all kinds of feedback and contributions. Thanks for using and supporting Quasar!
