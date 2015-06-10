# Sassy-Colours
SASS/SCSS colour defintiions for brands, CSS named colours and more

## Introduction

A SASS/Compass collection of named colours for world wide brands, technology systems, programming languages and more.

Colours include those for:

- web frameworks such as JQuery
-- $colour-jquery-black:             #333333
-- $colour-jquery-primary:           #0769ad
-- $colour-jquery-secondary:         #7acef4
- corporations such as Google.
-- $colour-google: #4285f4
-- $colour-google-2: #db4437
-- $colour-google-3: #f4b400
-- $colour-google-4: #0f9d58
-- $colour-google-5: #e7e6dd

## Reasoning

## Contributing

Fork a branch, add the brand colour definitions to the file.
When possible make a note of where/how colour was discovered (eg, web colour picker, Photoshop CC, Branding guide) with relevant URI where possible.

## Naming issues

Format of these files is in one of the standard forms:

 * $colour-NAME:                      #HEXCODE;
 * $colour-NAME:                      rgb(Red,Green,Blue);
 * $colour-NAME:                      rgba(Red,Green,Blue,Alpha);

In the first instance, colours will use the UK/Australian English/French spelling for colour over the American English color.

If you have a GREY/GRAY variant, ensure the alternative spelling points to the first version:

Example:

 *    $colour-grey-50:            #777;
 *    $colour-gray-50:            $colour-grey-50;


To Do:
Colour mapping: $colour-* to $color- [$colour-black = $colour-black]
