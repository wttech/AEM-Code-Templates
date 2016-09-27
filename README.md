# Code Templates

### Goal

Boost AEM components development

![Code Templates](https://github.com/Cognifide/AEM-Code-Templates/blob/master/img.png)


### What is it and how to use it

*Code templates* are list of reusable and parameterized code snippets. The feature is well-known for all developers. You use it every time when you create *loops*/*conditions* in Java classes.
The custom **code templates** are available in *xml* files only. Just type **aem** in a *xml* file and select the template which you want.


### Existing scripts support:
 * the most popular Touch UI widgets (e.g. *textfield*, *selection*, *image*, *pathbrowser*). They cover at least 80% cases.

 * Touch UI dialog structure and dialog's tabs

 * AEM component definition (structure of the *.content.xml*, *\_cq\_editConfig.xml* and *_cq_template.xml* files)


### How to configure it

#### IntelliJ

1. Go to the following directory where **code templates** are stored

  * Windows: `<your home directory>\.<product name><version number>\config\templates`

  * Linux: `~/.<product name><version number>/config/templates`

  * OS: `~/Library/Preferences/<product name><version number>/templates`

2. Download the *widgets.xml* file from [the repository](https://github.com/Cognifide/AEM-Code-Templates/blob/master/IntelliJ/widgets.xml)

* Restart your IDE


#### Eclipse

1. Download the *templates.xml* file from [the repository](https://github.com/Cognifide/AEM-Code-Templates/blob/master/Eclipse/templates.xml)

* Open your IDE

* Go to `Window > Preferences > XML > XML Files > Editor > Templates`

* Click *Import* button and select the downloaded file


### Known issues

1. Eclipse IDE doesn't preserve template indents

  **Workaround**:

  * Open the following settings `Window >Preferences > XML > XML Files > Editor`

  * Check the `Split multiple attributes each on a new line` option

  * Set four spaces as the `Indentation size`
