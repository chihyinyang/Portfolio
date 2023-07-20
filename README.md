# Nutmeg interview assignment (Ria Yang)

## README Overview
* [Tasks](#Tasks)
* [Architecture](#Architecture)
* [Features](#Features)
* [Swift Package Manager](#Swift Package Manager)
* [API Doc](#API Doc)

## Tasks
- Using the `/posts`, `/comments` and `/users` resources that can be found on the [typicode api](https://jsonplaceholder.typicode.com) api, build an app that displays a list of posts and comments.
- Each post cell should display username and title, tapping on a cell should open a screen that display all comments on that post by fetching /posts/{postId}}/comments.
    - App architecture and good coding practices will be evaluated.
    - Unit testing is a must, UI testing encouraged.
    - The exercise should be completed using UIKit or SwiftUI.
    - The exercise should be shared by Google Drive / or any other non-public cloud repository.
    
## Architecture
- MVVM (Model–view–viewModel)
    
## Features
- Posts: Display `username` and `title` on a list)
- Comments: Tap on the cell to show the `comments` on the post)
- Accessibility: Support light/dark mode
- Unit Test
- UI Test(using SnapshotTesting)

## Swift Package Manager
Utilized `SnapshotTesting` in SPM to perform UI testing

## API Doc
[typicode api](https://jsonplaceholder.typicode.com) api
