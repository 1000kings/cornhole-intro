# cornhole-intro
CS50 website introducing the game of cornhole
by Christopher Manser

A current interest of mine is the backyard game of cornhole in which a player throws a 1lb bag 27 feet onto a board with a hole in it in an attempt to put the bag in the hole.  The aim of this website is to introduce new players to the basics of the game.  The site is designed as mobile-first with updates to the styles based upon larger screens.

Page 1 (index.html) of the site introduces the viewer to the game itself and to the basic rules of playing the game.  The page is two stacked columns on a mobile screen with the intro on top and rules below but converts to two side-by-side columns when the screen is large according to the BS4 lg pixel breakpoint.  The Rules section of the page using unordered lists to bulletpoint rules and nested lists to add more helpful information to each of the main rules.  For visual clarity the text color of the nested lists is changed.

Page 2 of the site introduces the viewer to the basics of the equipment that will be needed to play the game.  This page has two rows, one for describing the boards of the game and the other for describing the bags.  Each row has two columns with an image in the first column and the description in the sibling column.  Given the size of the content of each row the style does not change according to pixel breakpoints.

Page 3 of the site describes the activity of throwing a cornhole bag, including how to stand, how to grip the bag and the finishing release of the bag towards the board.  The page has an introductory div followed by stacked columns separating each of these three aspects of the throwing activity.  Each section is a column with an image stacked on top.  When the screen size is larger than the BS4 pixel breakpoint the page expands to have three side-by-side columns as opposed to the stacked columns.  Each column is topped by a title with a color background.

Page 4 of the site explains some basic cornhole terminology using a table to separate the word and the definition of the word.

All four pages are topped by a header and a menu underneath the header that allows the viewer to navigate to each of the four pages.  The pages with more content also include anchor points under the main menu to allow the viewer to jump down the page to lower sections.  Finally each page also includes pagination navigation at the bottom of the page to allow the viewer to navigate to the next page (or previous page) after reading through the page's content.
