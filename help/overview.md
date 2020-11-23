---
title: Overview
description: This is the article overview.
---

# 32-bit Acrobat DC SDK

Welcome to the 2020 32-bit Acrobat DC SDK!

The Acrobat SDK is a set of tools that help you develop software that interacts with Acrobat technology. The SDK contains header files, type libraries, simple utilities, sample code, and documentation. These tools provide several methods for developing software that integrates with Acrobat products, including JavaScript, plugins, and interapplication communication.

* **JavaScript**: Acrobat exposes much of the functionality of Acrobat and its plug-ins to the document author via JavaScript extensions. You can also access JavaScript objects, properties and methods through Visual Basic or C# to automate the processing of PDF documents. Acrobat defines several objects that allow your code to interact with the  application, a PDF document, or fields within a PDF document. The most commonly used objects control the Acrobat or Adobe Reader application, the JavaScript console, the PDF document, SOAP web services, databases, security, searches, and JavaScript events. JavaScript can be internal or external to a PDF, and its location controls the context in which processing occurs, when the scripts are loaded, how they are accessed, and their reusability. 
* **Plugins**: Plugins are dynamically-linked extensions to the product. They hook to the user interface in a number of ways and can be called for a variety of events. Write plugins in ANSI C/C++ with the Acrobat public APIs and place it in the Plug_ins folder or directory so that it's initialized during application startup. On Windows, plug-ins are DLLs. However, plug-in names must end in .API, not .DLL. On Mac OS, plug-ins are code fragments, whereas on UNIX, plug-ins are shared libraries.
* **Interapplication Communication (IAC)**: Write a separate application process that uses IAC to control app functionality. Windoes supports DDE and OLE, and Mac supports Apple events/AppleScript. IAC allows programs to control the app in much the same way a user would. You can also use IAC support to render a PDF file into an external application window instead of the product window. The IAC methods and events serve as wrappers for some of the core API calls in the SDK. On Windows, you can develop IAC applications using Visual Basic .NET, Visual C++ .NET, or Visual C# .NET. On Mac OS, you develop IAC applications using Xcode. CodeWarrior is not supported.

>[!TIP]
>
>The Acrobat DC SDK provides a large number of sample applications, plug-ins, and scripts to demonstrate how to use the SDK technologies. Reviewing the samples and [Link me Guide to SDK Samples](<https://www.adobe.com) may help you choose  JavaScript, plug-ins, or IAC functionality for a particular implementation.

Insert doc roadmap diagram

## Support and contacts

The Acrobat Developer Support team supports software development with the Acrobat DC SDK’s core APIs. Developers can purchase support via the [Adobe Creative Cloud Exchange Developer Support program](https://helpx.adobe.com/ie/support/programs/cc-exchange-developer-support.html). Supported SDK development activities include those for which the product is designed, tested, and licensed. Acrobat Developer Support does not support use cases that do not involve the Acrobat core API. 

Only the last two major SDK versions with interim updates are eligible for support. 

>[!NOTE]
>
>For non-programmatic issues, such as questions about installing, using, customizing, or deploying Acrobat, contact [Acrobat Technical Support](https://helpx.adobe.com/uk/contact/what-contact-options.html)