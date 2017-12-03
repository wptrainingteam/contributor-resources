The Make WordPress Training style guidelines are a reference point to maintain consistency while developing new lesson plans.

* * *

## Topics

*   [Content](#content)
*   [Structure](#structure)
*   [Assets](#assets)
*   [Formatting](#formatting)
*   [Issues](#issues)
*   [Accessibility](#accessibility)

* * *

## Content [#](#content)

### Resources

The Make WordPress Training lesson plans are a project of WordPress.org. As such, lesson plans should not incorporate content that refers to or details elements of the following unless the Training Team has collectively decided that an exception makes sense:

*   WordPress.com
*   Paid services and resources, including plugins and themes

### Tone

Write in **script format**. The reader should feel that the speaker is an instructor explaining something clearly to them. Address the audience directly by writing in the **second person** (i.e. you, not we). **Correct** _Log in to your WordPress Admin Screens._ **Incorrect** _Next, we need to log in to WordPress._

### Grammar

Standard English grammar should be used for all lesson plans unless a lesson plan is originally written in or translated into another language. If English is your second language, that is OK! The copy editing process includes editing for grammar usage. You should write lesson plans using:

*   complete sentences.
*   WordPress elements as regular nouns. For example, the words, theme, post, user, etc. are not proper nouns.
*   Oxford commas, which include a comma before the final conjunction, normally _and_ or _or_.
*   the active voice. There are times when the passive voice is appropriate, but they should be rare.

* * *

## Structure [#](#structure)

All lesson plans follow the same structure, which is described in detail on the [Anatomy of a Lesson Plan](/training/anatomy-of-a-lesson/) page. Specific formatting concerns may apply to each section as outlined below.

### Description

The **description** should be a short paragraph written in full sentences.

### Objectives

**Objectives** should be worded as actions that the student can do once they've finished. They should be presented in an unordered list, prefaced with the introductory text, "At the end of this lesson, you will be able to:". List Objectives as the completion of sentences that begin with the introductory text, with the first letter capitalized and a period at the end of each sentence. Objectives should use action verbs in accordance with [Bloom's Taxonomy](http://www.fresnostate.edu/academics/oie/documents/assesments/Blooms%20Level.pdf) (PDF). **Correct** At the end of this lesson, you will be able to:

*   Identify the files required to make a theme.

**Incorrect**

*   Students will know the files required to make a theme.

### Prerequisite Skills

**Prerequisite skills** should be presented in an unordered list. Preface the list of skills with the introductory text, "You will be better equipped to work through this lesson if you have experience in and familiarity with:". Skills should be listed as phrases, not sentences. The first letter of each phrase should be capitalized. **Correct** You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Ability to edit files with a text editor

**Incorrect**

*   ability to edit files with a text editor.

### Assets

**Assets** should be presented as links in an unordered list. There should _not_ be introductory text before the list of assets. Assets should be listed as phrases, not sentences. The first letter of each phrase, as well as the formal titles of any themes, products, etc., should be capitalized. Asset links should open in a new tab and should include the title attribute within each link. If there are no required assets, please list "None." **Correct**

*   [Twenty Thirteen theme](https://wordpress.org/themes/twentythirteen "Twenty Thirteen Theme")

**Incorrect**

*   [Twenty Thirteen Theme](https://wordpress.org/themes/twentythirteen)

### Screening Questions

**Screening questions** should be presented in an unordered list. There should _not_ be introductory text before the list of questions. Questions should be written as questions and use a question mark at the end of each sentence. The first letter of each question should be capitalized. **Correct**

*   Do you have at least a basic knowledge of HTML/CSS?

**Incorrect**

*   you have at least a basic knowledge of HTML/CSS

### Teacher Notes

**Teacher Notes** should be presented in an unordered list. There should _not_ be introductory text before the list of notes. Notes should be written in full sentences with the first letter capitalized and a period at the end of each sentence. The first list item should always be a time estimate and should be formatted following the same pattern as the example below. The time estimate should not be written as a full sentence. **Correct**

*   **Time Estimate:** 30 minutes
*   The preferred answers to the screening questions is “yes.” Participants who reply “no” to all 4 questions may not be ready for this lesson.

**Incorrect**

*   preferred answers to the screening questions are “yes;” participants who reply “no” to all 4 questions may not be ready
*   this lesson will take about thirty minutes

Add a final list item as follows to indicate which version of WordPress that you built the lesson plan with. This will make it easier over time to maintain the lesson plan as WordPress evolves. Each time someone reviews or updates the lesson plan, particularly when updating screen captures, you should update the version number.

*   Built using WordPress version **4.7.3**

### Hands-on Walkthrough

The **hands-on walkthrough** should be presented in a conversational tone. Split the content into logical sections, using

### tags to designate headers.

* * *

rules should be used to separate each section. Use

#### tags to designate subheaders within these sections.

### Exercises

The **exercises** should be presented using **tags to designate the task for each exercise. Questions about each exercise should be presented in an unordered list. Questions should be written as questions and use a question mark at the end of each sentence. The first letter of each question should be capitalized. If there are not questions related to each exercise, then the exercises should be presented as an ordered list.**

### Quiz

**Quiz questions** should be presented using **tags around each question. Questions should be written as questions and use a question mark at the end of each sentence. The first letter of each question should be capitalized.** **Possible answers** to quiz questions should be presented in an ordered list. Answers can be phrases, sentences, code samples, etc. If the answer is a phrase or sentence, then the first letter of each answer should be capitalized. Correct formatting for a quiz question is as follows: **When developing for WordPress, what files should you never edit?**

1.  Core WordPress files
2.  Plugin files
3.  Theme files
4.  All of the above

**Answer:** 4\. All of the above

* * *

## Assets [#](#assets)

### Approved Themes

Use one or more of the following themes in your demos:

*   [Twenty Twelve theme](http://wordpress.org/themes/twentytwelve)
*   [Twenty Thirteen theme](http://wordpress.org/themes/twentythirteen)
*   [Twenty Fourteen theme](http://wordpress.org/themes/twentyfourteen)
*   [Twenty Fifteen theme](http://wordpress.org/themes/twentyfifteen)
*   [Twenty Sixteen theme](http://wordpress.org/themes/twentysixteen)
*   [Storefront theme](https://wordpress.org/themes/storefront/) (only for WooCommerce lesson plans)

### Images

Images should be full size. Don’t include thumbnails that readers have to click on to see unless absolutely necessary.

#### Screenshots

All screenshots that show an operating system should be taken using a Mac computer. All other screenshots can be taken using other operating systems. To take screenshots that look great, resize your browser window. By resizing down, you can take screenshots of the specific areas of the screen that you are referring to. All browser elements should be cropped out of the image. The exception to this guideline is if you need to show a code inspector in your screenshot.

##### Code Inspectors

If you need to show a code inspector in your screenshot, please use [Firebug](https://getfirebug.com/) or Chrome's native inspector. If a particular code inspector is required for students to follow along with the lesson plan, indicate this requirement in the Teacher Notes for the lesson plan.

##### Notations

All notations on screenshots should be make using [Skitch](https://evernote.com/skitch/). Please use the default arrows and icons that come with Skitch and the default red color as the primary color for any notations. If you need a secondary color for the annotations, use the default blue color.

#### Placeholders

Placeholder images should be sourced from [Placekitten](http://placekitten.com/).

#### Naming Conventions

All filenames should be descriptive of the image, all lowercase, and contain no spaces: e.g. `kitteninbasket.jpg` is consistent with the style guide and `Kitten in Basket.jpg` is not.

### Content

#### Sample Content

If you need to include placeholder content in your demo theme, use the [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml). There is inline documentation at the top of this file with instructions on how to import the content into your WordPress installation. In instances where the demonstration requires sample content to be added during the demo or in the exercises, the Theme Unit Test Data may not be appropriate to use in isolation. In this case, use the [lipsum.com](http://www.lipsum.com/) Lorem Ipsum generator to create this content.

#### Sample Plugins

If you need to include placeholder plugins in an example, use the [Monster Widget](https://wordpress.org/plugins/monster-widget/) to add the default WordPress plugins to the sidebar of your lesson plan's sample theme.

### Colors

When producing diagrams, charts, etc. use the official WordPress color palette:

<section style="width: 300px;">

#### Blue

*   Pantone 7468
*   CMYK 97, 44, 26, 3
*   Hex #21759b
*   RGB 33, 117, 155
*   HSL 199, 79%, 61%

</section>

<section style="width: 300px;">

#### Orange

*   Pantone 1665
*   CMYK 6, 86, 100, 1
*   Hex #d54e21
*   RGB 213, 78, 33
*   HSL 15, 85%, 84%

</section>

<section style="width: 300px;">

#### Grey

*   Pantone Black 7
*   CMYK 65, 60, 60, 45
*   Hex #464646
*   RGB 70, 70, 70
*   HSL 0, 0%, 27%

</section>

<section style="width: 300px;">

#### Light Blue

While not a part of the official WordPress color palette, this light blue is commonly used as an accent color.

*   CMYK 16, 3, 0, 0
*   Hex #d3e7f8
*   RGB 211, 231, 248
*   HSL 208, 15%, 97%

</section>

* * *

## Formatting [#](#formatting)

### Basic Conventions

*   Use [W3C HTML and CSS Recommendations](http://www.w3.org/standards/webdesign/htmlcss) to separate document markup (HTML) from inline styling preferences (CSS).
*   Use ordered and unordered HTML lists.
*   Use HTML header tags in the correct order from h2 – h6\. Do not add inline styling to headers.
*   When referring to menu items, use the format Pages > Add New.
*   Do not use empty paragraph or header tags to force spacing between content elements

### Emphasized Text

*   Use `strong` tags to make important points stand out or to indicate instructions: e.g. Create a **Child Theme** that is a **“child”** of another theme (the Parent Theme).
*   If you want to alert the user to something, use the following short codes to wrap the text: [info]This is an informational message and uses the [ info ] short code. [/info] [tip]Use the [ tip ] short code to highlight tips.[/tip] [alert]The [ alert ] short code is for alerting readers to important messages.[/alert] [warning]When something is particularly precarious, use the [ warning ] short code.[/warning]

Use begin and end tags, like this: [ info ]Here is some information.[ /info ] [warning]To get the raw emphasized text short codes to appear on this page so that you can see them, we added a space between the brackets and the short code name. Omit those spaces when using the short codes![/warning]

### Code Examples

Use shortcodes for each language to wrap code samples. For indentation, use 4 spaces.

#### PHP

Use the shortcode [php] [/php]. If your PHP code sample includes any HTML, including HTML comments, please use the HTML shortcode. [php] [/php]

#### JavaScript

Use the shortcode [js] [/js]. [js] jQuery( "body" ) .html( "This line is indented with 4 spaces.") [/js]

#### HTML

Use the shortcode [html] [/html]. [html] This line is indented with 4 spaces. [/html]

#### CSS

Use the shortcode [css] [/css]. [css] p { /* This line is indented with 4 spaces */ color: #ff0000; } [/css]

#### Generic Code Samples

Use the shortcode [code] [/code] for generic code samples with line numbers and the HTML elementfor generic code samples with inline formatting and no line numbers. [code] This is some generic code with line numbers. [/code]

<pre>This is some generic code without line numbers and with the word <span style="color: red;">red</span> highlighted.
</pre>

#### File Names

File names and other inline code snippets should all be wrapped in the HTML element. **Correct** `style.css` **Incorrect** _style.css_

* * *

## Issues [#](#issues)

If you encounter a situation where you need to leave a lesson in an unfinished state--such as if you need input on some aspect of the lesson or later need to update images--you should add a To Do section _at the top of the lesson_ using the info short code (see the Emphasized Text section in [Formatting](#formatting) above). Format the To Do section like this: [info]**To Do**

*   Replace images captured in Windows with those captured on a Mac to be consistent with the existing images
*   Resolve the issues with the best way to fitzblat the snagglepark

[/info] Here is how the above To Do section would be structured:

<pre>[info]**To Do**</pre>

*   *   Replace images captured in Windows with those captured on a Mac to be consistent with the existing images

*   *   Resolve the issues with the best way to fitzblat the snagglepark

  [/info]

* * *

## Accessibility [#](#accessibility)

*   Where possible follow the [W3C's Web Content Accessibility Guidelines](http://www.w3.org/TR/UNDERSTANDING-WCAG20/intro.html#introduction-fourprincs-head).

### General Items

*   Do not underline words that are not links.
*   Do not use all caps within content.
*   Use HTML to convey textual information as much as possible instead of using PDF or image formats.

### Links

Use descriptive links instead of generic text: e.g. "We are using the [Twenty Thirteen theme](http://wordpress.org/themes/twentythirteen)." is consistent with the style guide and "Find the Twenty Thirteen theme [here](http://wordpress.org/themes/twentythirteen)." is not. On pages that contain multiple links, ensure that each link text is unique – unless you are linking to the same resource in more than once place.

### Images

Use descriptive alt text on all images: e.g. "page attributes section of edit page screen" and not "image" or other text which does not adequately describe the the image.

### Multimedia

Make sure equivalent alternatives are available for audio/video content. For example, use Closed Caption service for videos.

### Abbreviations

Avoid the use of jargon, abbreviations and acronyms whenever possible. If you really do need to use an abbreviation, use the full, expanded version first, followed by the abbreviation in parentheses (brackets). Alternatively, use correct abbreviation markup such as: [html]<abbr title="World Wide Web Consortium">W3C</abbr>[/html]