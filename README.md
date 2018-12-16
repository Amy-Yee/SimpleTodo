# Pre-work - *Simple To-do*

**Simple To-do** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Amy Yee**

Time spent: **2.5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/d4Yg7c0.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** The Android app development platform seems easy for a beginner to learn, yet takes practice to truly master. The platform seems like a combination of visual and text-based programming. Similar to LabView programming, Android programming has drag-and-drop programming. Like text-based programming, Android programming allows systematically creating functions from a given event. 

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** I understand an adapter as a dynamic data type that bridges between the user interface and the underlying code. The shape or content of an adapter can change after processing input or events that occur from the user's end. The adapter is important because they are unique to the specific functions of the application. For example, an ArrayAdapter could be used as a photo grid in one application, or a to-do list in another. `convertView` "recycles" View objects, as opposed to generating a new object each time a user wants to make a change. In the context of this app, a new `ArrayAdapter` does not have to be regenerated each time a user decides to add/remove an item to the to-do list; the item is simply written/popped from the list and dynamically shown in the `ArrayAdapter`.

## Notes

Initially, I had trouble with the setup because I did not know where to download the Pixel emulator. However, I found additional videos that indicated I first had to begin a project.

## License

    Copyright 2018 Amy Yee

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
