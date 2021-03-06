---
layout: post
title: Toolbox Control | xamarin | Syncfusion
description: Syncfusion Xamarin Toolbox to add the Syncfusion Xamarin (Xamarin.Forms) controls in your project without coding in the Visual Studio designer.
platform: xamarin
control: Syncfusion Extensions
documentation: ug
---

# Xamarin Toolbox control

Syncfusion provides the customized **Visual Studio Toolbox** for the Syncfusion Xamarin platform to add the Syncfusion Xamarin (Xamarin.Forms) controls in your project. It supports Microsoft Visual Studio 2017 and later. The Syncfusion Xamarin toolbox helps you use the Syncfusion controls without coding in the Visual Studio designer.

I> The Syncfusion Xamarin Toolbox is available from v16.2.0.41.

Create the Xamarin or Syncfusion Xamarin project. The following steps helps you add the Syncfusion controls through the Visual Studio Toolbox:

1. To open Syncfusion Toolbox Wizard, follow either one of the options below:

   **Option 1:**  
   Click **Syncfusion Menu** and choose **Essential Studio for Xamarin > Launch Toolbox…** in **Visual Studio**.

   ![Syncfusion Xamarin Custom Toolbox via Syncfusion menu](Toolbox_images/Syncfusion_Menu_Toolbox.png)

   N> In Visual Studio 2019, Syncfusion menu is available under Extensions in Visual Studio menu.

   **Option 2:**  
   Choose **View > Other Windows > Syncfusion Toolbox** in **Visual Studio**.

   ![Syncfusion Xamarin Custom Toolbox menu](Toolbox_images/Toolbox-img1.jpeg)
   
2. Click **Syncfusion Toolbox** menu item, the Syncfusion Toolbox wizard appears. The Syncfusion control will be enabled when opening the Xamarin.Forms designer page. There is no Syncfusion control appears until open the appropriate .xaml file from the Xamarin shared/.NET Standard /PCL project.

   ![Syncfusion Xamarin Toolbox wizard](Toolbox_images/Toolbox-img2.jpeg)

3. The required Syncfusion controls design (.xaml) snippet and namespace will be added by drag and drop the required control from the toolbox to the designer.

   ![Required Syncfusion control code snippet and namespace in design page](Toolbox_images/Toolbox-img3.jpg)

   Also, the required control Syncfusion Xamarin NuGet packages will be installed automatically when drag and drop the control to the designer to render the Syncfusion control.

4. If you installed the trial setup or NuGet packages from nuget.org you have to register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.