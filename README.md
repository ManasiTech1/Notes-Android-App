# Notes-Android-App

This repository contains the code for a Notes Android App, a simple yet effective application to manage your personal notes. The app allows users to add, display and delete notes efficiently. It uses SharedPreferences for local data persistence and is built with a single activity, making it lightweight and easy to maintain.

## Features
- Single Activity Design: The app uses one activity to handle all its functionality.
- Add Notes: Users can add notes with a title and content.
- Delete Notes: Long-press on a note to delete it.
- Local Storage: Notes are saved locally using SharedPreferences, ensuring persistence across app sessions.
- Dynamic UI: Notes are dynamically displayed in a scrollable view.

## Key Methods in MainActivity
- saveNote(): Adds a new note and updates the UI and storage.
- deleteNoteAndRefresh(Note note): Deletes a note and refreshes the notes view.
- saveNotesToPreferences(): Saves all notes to SharedPreferences.
- loadNotesFromPreferences(): Loads notes from SharedPreferences.
