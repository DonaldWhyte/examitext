[![Examitext](https://github.com/DonaldWhyte/examitext/raw/wiki/header.png)]

A web application which examines text documents, chat logs and source code to provide meaningful statistics about them.

[![examitext screenshot](https://github.com/DonaldWhyte/examitext/raw/wiki/Thumbnail%20-%20Examitext%20Screenshot%203.png)]

Examitext is a tool which analyses three different kinds of textual data - text documents, chat logs and source code - providing various statistics and information on the data. Both the back-end processing and the front-end interface are developed purely in JavaScript, and can be run in any modern browser. In addition to that, there is an alternate PHP version of Examitext, which allows users to input local or remote (given a URL) files, rather than pasting in the text directly.

The latest version of Examitext can be downloaded from the project's [GitHub repository](https://github.com/DonaldWhyte/examitext).

### Features

* Natural Language Analysis
    * scans text from eight languages -- English, French, German, Italian, Spanish, Portuguese, Swedish and Finnish
    * stems words to their base form to prevent redundant entries
    * filters common words using stoplists
* Programming Language Analysis
    * HTML parser, which can detect used CSS IDs/classes/inline styles
    * loose parsing for JavaScript, Java, C# and C++
    * calculating inheritance hierarchy for object-oriented languages
* Text Documents
    * paragraph size distribution and trends
    * most frequently occurring topics
    * use of punctuation
* Chat Logs
    * speaking habits of each participant of the conversation (e.g. average message length, average number of consecutive messages, etc.)
    * how much each participant contributes to the conversation
    * most talked about topics and frequency/relative frequency of most spoken words for each participant (after stemming/filtering)
* Source Code
    * HTML
        * Listing most used tags/CSS classes
        * Getting number of resources (e.g. stylesheets, scripts, images) are referenced
    * All Languages
        * Calculating how much basic operations (e.g. =, +, -, %) are in the source code
        * Calculating how many heap memory allocations are performed (via 'new')
        * Determining highest quadratic time complexity to aid in algorithm analysis/optimisation
    * JavaScript
        * Scanning global and local functions declared and determining how much they're used
    * Java/C#/C++
        * Scanning document for all declared classes/interfaces, as well as their methods and properties
        * Building and displaying an inheritance hierarchy for all the classes defined

### Installation

No installation required. Simply open `examitext.html` in any modern browser to
run the application.

### Licensing

Please read the file called `LICENSE` for the details on Chat Analyser's license.

JQuery and Easy Tooltip are licensed under the MIT License.

Highcharts is licensed under the Creative Commons Attribution-NonCommercial 3.0
License.

jsSnowball and John Resig's HTML parser are licensed under the Mozilla Public
License. Details available here: http://www.mozilla.org/MPL/

#### Authors and Contacts

The project is managed and developed by Donald Whyte. To submit bugs,
suggestions or feedback about Chat Analyser, go to the project's [GitHub repository](https://github.com/DonaldWhyte/examitext).
