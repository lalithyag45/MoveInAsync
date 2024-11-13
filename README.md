# MoveInAsync

## Introduction
Welcome to Move in Async! This app is designed to help you manage and schedule your daily tasks efficiently. As part of learning iOS development, this app demonstrates the basics of UI components and their implementation in Swift.

## Features
<ul>
<li> Add Schedule: Easily add new schedules with type, time, status, and date. </li>
<li> View Schedules: View a list of all your schedules in a table view. </li>
<li> Cancel Schedule: Cancel a schedule by tapping the cross button and confirming the deletion.</li>
<li> Settings Menu: Access a settings menu with a profile view and additional options.</li>
</ul>

## Installation
To get started with Move in Async, follow these steps:
<ul>
<li><h3> Clone the repository: </h3>
  git clone https://github.com/lgutha/MoveInAsync.git </li>

<li><h3> Open the project in Xcode:</h3>
  <li> open UIProject.xcodeproj </li>

  Build and run the app on your simulator </li>
</ul>

## KeyComponents
<ul>
<li><h3> ViewController </h3>
The ViewController class manages the main interface of the app, including the title label, add button, settings button, and table view. It implements the UITableViewDataSource, UITableViewDelegate, AddScheduleDelegate, and ScheduleCellDelegate protocols.
  </li>
<li>
  <h3>ScheduleCell</h3>
The ScheduleCell class is a custom UITableViewCell that displays the details of a schedule, including type, time, date, and status. It also includes a cross button for canceling the schedule.
  </li>
<li>
  <h3>SideMenuViewController</h3>
The SideMenuViewController class provides a side menu interface with a profile image, name label, employee ID label, and an ad-hoc OTP label. The menu can be dismissed by tapping outside the menu or dragging it down.
  </li>
<li>
  <h3>AddScheduleViewController</h3>
The AddScheduleViewController class allows users to add new schedules by entering the type, time, status, and date.
  </li>
</ul>

