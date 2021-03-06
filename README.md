# 'Quick Add Reference' for CodeRush # 

### Please Note: This project is now considered obsolete. It's source is published here for reference only.

A plugin to provide a quicker way to add some of the more common assemblies to your project. Loads in < 2 seconds.

![](Screenshots/QuickAddReference.png)

### Usage ###

Assuming installation is done correctly, '**Quick Add Reference**' should be available as a DXCore action. This action can be bound to a hotkey (I used Ctrl+AltT in testing). 

Triggering QuickAddReference leads to the main "Quick Add Reference" dialog which includes different tabs designed to show you different lists of potential references.

Select one or more references and hit the add button.

### Tabs ###
Each tab provides a different list of potential references which you can add to the current project.
#### Solution Tab ####
The solution tab provides a list of references already in use in one or more of the projects in your solution.
#### Recent Tab ####
The recent tab will contain the 20 most recent assemblies added to a project using QuickAddReference. 
#### Common Tab ####
This is a user configurable tab which by default contains the following assemblies.

 * System.Configuration.dll
 * System.Data.dll
 * System.Data.DataSetExtensions.dll
 * System.Xml.dll
 * System.Xml.Linq.dll

#### Win Tab 
This is a user configurable tab which by default contains the following assemblies.

 * System.Drawing.dll
 * System.Windows.Forms.dll

#### Web Tab 
This is a user configurable tab which by default contains the following assemblies.

 * System.Web.dll
 * System.Net.dll
 * System.Web.Extensions.dll
 * System.Web.Services.dll

More tabs will follow.

### Limitations ####
 * COM references cannot be added.
 * Project references cannot be added.
