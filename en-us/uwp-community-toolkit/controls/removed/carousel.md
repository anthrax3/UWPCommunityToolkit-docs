---
permalink: /en-US/controls/carousel.html
title: Carousel XAML Control for UWP Community Toolkit
description: The Carousel Control is slideable application that lets users add interactive navigation XAML UI to applications. 
Keywords: carousel, menu, CarouselControl, Carousel, control, image, windows, application, XAML, UI, slideable, UWP, toolkit 
defaultsearch.product:  eADQiWindows 10XVcnh 
---

# Carousel XAML Control
The **Carousel Control** is a slideable application that lets developers add interactive navigation UI to their application. Developers can navigate through a list, add and remove items dynamically, smooth animations create vertical and horizontal transitions, and customize item paths. 

### How it Works
The Carousel Control displays modern and visually appealing, tile-like items. Carousel items can be styled as either *Normal*, *Active* or *HotTracked*, or programmed to automatically scroll along customized paths.  An example is the *Windows 10 UI* (The tiles that appear when the user presses the Windows key).    
<p> **Note:** The following section provides required code that must be used when creating a Carousel Control for Windows application development.<p> 

 
## Syntax 
```xaml
	<controls:Carousel
	        Name="CarouselControl"
	        MaxItems="10"
	        AspectRatio="1.5"
	        MaxHeight="200"
	        AlignmentX="Left"
	        GradientOpacity="0.1"/>
```          

## Example Image
![Carousel Control Items](/resources/images/CarouselControl.GIF)

## Example Code

[Carousel Sample Page](https://github.com/Microsoft/UWPCommunityToolkit/tree/master/Microsoft.Windows.Toolkit.SampleApp/SamplePages/Carousel)

## Default Template 
[Carousel XAML File](https://github.com/Microsoft/UWPCommunityToolkit/blob/master/Microsoft.Windows.Toolkit.UI.Controls/Carousel/Carousel.xaml) is the XAML template used in the toolkit for the default styling.

## Platforms 

Windows 10 SDK 10240 or higher

## API 

Please view the [toolkit sample application](https://github.com/Microsoft/UWPCommunityToolkit/tree/master/Microsoft.Windows.Toolkit.SampleApp) for the UWP Community Toolkit for current samples and example code.