![image](https://microsoft.github.io/microsoft-ui-xaml/img/winui-logo.png)

# WinUI-3-xaml-templates
A Collection of XAML Templates, designed for WinUI.

[![Build Status](https://dev.azure.com/stmoy/Xaml%20Controls%20Gallery/_apis/build/status/XAML%20Controls%20%20Gallery%20-%20CI%20Tests?branchName=master)](https://dev.azure.com/stmoy/Xaml%20Controls%20Gallery/_build/latest?definitionId=2&branchName=master)

Used in [UWP Development](https://docs.microsoft.com/en-us/windows/uwp/get-started/universal-application-platform-guide), [XAML](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/xaml/?view=netdesktop-5.0) has evolved from XML, giving power to developers to add [Microsoft's WinUI](https://microsoft.github.io/microsoft-ui-xaml/about.html) into their own UWP apps. 

## WinUI Community Calls

The WinUI community call is your monthly opportunity to learn about native UX development for Windows with WinUI.

In these calls we’ll discuss the WinUI roadmap, our status and your feedback.

You can watch them online here on YouTube at the [Windows Developer channel](https://www.youtube.com/channel/UCzLbHrU7U3cUDNQWWAqjceA).

Add the event to your calendar: [ICS calendar file](communitycalls/WinUICommunityCall.ics)

## Using WinUI 3

You can build new Windows apps using WinUI 3, which ships as a part of the Windows App SDK. The latest available stable release is the Windows App SDK 0.8 (previously called Project Reunion). With this release, you can ship production Desktop apps to the Microsoft Store.

See the [installation instructions](https://docs.microsoft.com/windows/apps/windows-app-sdk/set-up-your-development-environment), and guidelines on [creating your first WinUI 3 app](https://docs.microsoft.com/windows/apps/winui/winui3/create-your-first-winui3-app). 


## Requirements:

- Visual Studio 2019
- UWP App Development Kit
- WinUI Repository Clone

## Installation: 

- Select the theme you want to use from the repository
- Use the code for your project in Visual Studio.

**OR**

- Clone this repository in Visual Studio.
- Select and use the template you want.

## Using WinUI 2
You can download and use WinUI packages in your app using the NuGet package manager: see the [Getting Started with the Windows UI Library](https://docs.microsoft.com/uwp/toolkits/winui/getting-started) page for more information.

### Packages

| NuGet Package | Build Status | Latest Versions | Documentation |
| --- | --- | --- | --- |
| [Microsoft.UI.Xaml](https://www.nuget.org/packages/Microsoft.UI.Xaml) <br /> Controls and Fluent Design for UWP apps | [![Build Status](https://dev.azure.com/ms/microsoft-ui-xaml/_apis/build/status/WinUI-Public-MUX-CI?branchName=main)](https://dev.azure.com/ms/microsoft-ui-xaml/_build/latest?definitionId=20?branchName=main) | [![latest stable version](https://img.shields.io/nuget/v/Microsoft.UI.Xaml.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml) <br /> [![latest prerelease version](https://img.shields.io/nuget/vpre/Microsoft.UI.Xaml.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml/absoluteLatest) | [2.5 release](https://docs.microsoft.com/windows/apps/winui/winui2/release-notes/winui-2.5) |
| [Microsoft.UI.Xaml.Core.Direct](https://www.nuget.org/packages/Microsoft.UI.Xaml.Core.Direct) <br /> Low-level APIs for middleware components | | [![latest prerelease version](https://img.shields.io/nuget/vpre/Microsoft.UI.Xaml.Core.Direct.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml.Core.Direct/absoluteLatest) | [2.0 prerelease](https://docs.microsoft.com/uwp/api/microsoft.ui.xaml.core.direct) |

You can also build a WinUI package yourself from source. See [Contributing to the Windows UI Library](CONTRIBUTING.md) for more information on building and contributing to WinUI.

## WinUI features

### Benefits

WinUI 2 provides some useful benefits when building apps for Windows 10:

1. **Helps you stay up to date**  
WinUI helps keep your app up to date with the latest versions of key controls and features of [UWP XAML](https://docs.microsoft.com/windows/uwp/xaml-platform/xaml-overview) and the [Fluent Design System](https://www.microsoft.com/design/fluent)

2. **Provides backward compatibility**  
WinUI is backward-compatible with a wide range of Windows 10 versions: you can start building and shipping apps with new XAML features immediately as soon as they're released, even if your users aren't on the latest version of Windows 10

3. **Makes it simpler to build version adaptive apps**  
You don't need version checks or conditional XAML markup to use WinUI controls or features: WinUI automatically adapts to the user's OS version

### Version support

The Microsoft.UI.Xaml 2.4 NuGet package requires your project to have TargetPlatformVersion &gt;= 10.0.18362.0 and TargetPlatformMinVersion &gt;= 10.0.15063.0 when building. 

Your app's users can be on any of the following supported Windows 10 versions:

* Windows 10 1703 - Build 15063 (Creators Update aka "Redstone 2") and newer (including Windows Insider Previews)

Some features may have a reduced or slightly different user experience on older versions.

For WinUI 3, your app's users must be on Windows 10 1809 - Build 17763 or newer (including Windows Insider Previews).

## Roadmap

For info on the WinUI release schedule and high level plans please see the [Windows UI Library Roadmap](docs/roadmap.md).

## WinUI 3 is a part of the Windows App SDK family
The [Windows App SDK](https://github.com/microsoft/ProjectReunion) is a set of libraries, frameworks, components, and tools that you can use in your apps to access powerful Windows platform functionality from all kinds of apps on many versions of Windows. The Windows App SDK combines the powers of Win32 native applications alongside modern API usage techniques, so your apps light up everywhere your users are. 
 
Other Windows App SDK components are: [WebView2](https://docs.microsoft.com/microsoft-edge/webview2/),  [MSIX (MSIX-Core)](https://docs.microsoft.com/windows/msix/overview), [C++/WinRT](https://github.com/microsoft/cppwinrt), [Rust/WinRT](https://github.com/microsoft/winrt-rs), and [C#/WinRT](https://github.com/microsoft/cswinrt). If you'd like to learn more and contribute to Windows App SDK, or have **UWP/app model related questions**, visit our [Github repo](https://github.com/microsoft/ProjectReunion). 

## Data/Telemetry

This project collects usage data and sends it to Microsoft to help improve our products and services. See the [privacy statement](privacy.md) for more details.

For more information on telemetry implementation see the [developer guide](docs/developer_guide.md#Telemetry).


### Credits

- WinUI Logo: [Microsoft](https://microsoft.com/)
- WinUI and Visual Studio are trademarks of Microsoft Corporation and are subjected to copyrights.
