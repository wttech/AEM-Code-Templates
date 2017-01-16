![Cognifide logo](http://cognifide.github.io/images/cognifide-logo.png)

[![Apache License, Version 2.0, January 2004](https://img.shields.io/github/license/cognifide/aet.svg?label=License)](http://www.apache.org/licenses/)

# Code Templates

### Goal

Boost AEM components development

<p align="center">
  <p>Touch UI templates demo<p>
  <img src="misc/demo/demo.gif" alt="Code Templates"/>
</p>


### What is it and how to use it

*Code templates* are list of reusable and parameterized code snippets. The feature is well-known for all developers. You use it every time when you create *loops*/*conditions* in Java classes.

### Template types

1. [Touch UI](https://github.com/Cognifide/AEM-Code-Templates/tree/master/TouchUI) templates

 Provide templates for Touch UI dialogs and widgets which could be used inside the dialog.

2.  [Component Files](https://github.com/Cognifide/AEM-Code-Templates/tree/master/ComponentFiles) templates

 Provide basic definition of the AEM component files like: `.content.xml`, `_cq_template.xml`, `_cq_editConfig.xml`.

3.  [HTL](https://github.com/Cognifide/AEM-Code-Templates/tree/master/HTL) templates

 Provide templates for HTML Template Language (HTL)

### How to install

#### IntelliJ

1. Automatic Import

  1. Download [the liveTemplates.jar file](https://github.com/Cognifide/AEM-Code-Templates/blob/master/misc/releases/intellij/liveTemplates-2.0.0.jar)

  2. Open your IDE

  3. Go to `File > Import Settings`

  4. Choose the file downloaded in the fist step and click `OK`

2. Manual Import

  1. Go to the following directory where **code templates** are stored on you computer

    * Windows: `<your home directory>\.<product name><version number>\config\templates`

    * Linux: `~/.<product name><version number>/config/templates`

    * OS: `~/Library/Preferences/<product name><version number>/templates`

  2. Download the **.xml* containing templates definition file from the repository

  3. Put the downloaded file to the directory from the first point

  4. Restart your IDE if it is running


#### Eclipse

1. Download the **.xml* containing templates definition file from the repository

2. Open your IDE

3. Go to `Window > Preferences > XML > XML Files > Editor > Templates`

4. Click *Import* button and select the downloaded file

### Change log

1. Version 2.0.0 Date 16.01.2017

  `HTL` templates provided

2. Version: 1.0.0 Date: 29.09.2016

 `Touch UI` and `Component Files` templates provided
