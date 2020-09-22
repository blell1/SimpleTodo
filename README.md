# Prework SimpleTodo
**SimpleTodo** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Blake Eller**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **successfully add and remove items** from the todo list
* [X] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [X] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://imgur.com/a/mgkKrf6' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [RecordIt](https://recordit.co/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** 
Up til now, i had only used python for coding. Python is easy and intuitive, with the code looking almost like plain text.
Coding with Java is so much more complicated than coding with python, it's unbelievable. I had heard people refer to python as a "simple" coding language, 
but i thought they were exaggerating. As for the program itself, Android Studio, it was fairly similar to all the other platforms i used. 
There was nothing particualarly complicated about the android app development platform itself, just the language it used.

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android?
Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:**
In this context, an adapter is a class of functions that does exactly what it sounds like. It adapts the Recycler view to the changes made in the main activity.
Without the adapter, i could still have a text box and an add button and a list of items, but they wouldn't interact at all.
The "convertView" method allows for editing items in the recyclerview, and the "getView" determines what that item actually is.


## Notes

Describe any challenges encountered while building the app.
So many technical errors. Literally none of the programs worked on the first install. Not one.

## License

    Copyright [2020] [Blake Eller]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
