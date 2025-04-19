Project 7 - Task Manager

Submitted by: Ronald Milgo

Task Manager is an app that allows users to manage their tasks in an organized way. Users can add, edit, and delete tasks, track task completion status, and view tasks based on due dates in a calendar view. The app also persists task data even when the application is closed and relaunched.

Time spent: 2 hours spent in total

Required Features

The following required functionality is completed:

 App displays a list of tasks
 Users can add tasks to the list
 Session persists when the application is closed and relaunched (tasks don’t get deleted when closing the app)
 Note: You have to quit the app, not minimize it, in order to see the persistence.
 Tasks can be deleted
 Users have a calendar view via a navigation controller that displays tasks
The following additional features are implemented:

 Tasks can be toggled between completed and incomplete states
 User can edit tasks by tapping on the task in the feed view
 Tasks are sorted by their completion status and due dates
 Completed tasks are moved to the bottom of the task list with animation
Video Walkthrough

Here is a reminder on how to embed Loom videos on GitHub. Feel free to remove this reminder once you upload your README.

Guide.

Notes

Challenges encountered:

Implementing UserDefaults for data persistence was tricky initially, especially ensuring that the app saves and loads tasks correctly.
Handling task sorting based on completion status and due dates required careful planning to ensure that completed tasks appear at the bottom without affecting the UI responsiveness.
Setting up tab bar navigation with both a task list and calendar view was slightly confusing initially, but with proper linking in the storyboard, everything worked smoothly.
License

Copyright 2025 Ronald Milgo

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
