# Notes App

A Flutter mobile application for creating, editing, and deleting notes.

## Features

### Grade 4 Requirements ✅
- **Text input field**: Users can enter text in a multiline text field
- **Save button**: "Save Note" button to save entered text
- **Notes list**: Saved notes are displayed below in a scrollable list

### Grade 5 Requirements ✅
- **Delete notes**: Each note has a delete button with confirmation dialog
- **Edit notes**: Each note has an edit button to modify existing content

## How to Run

### Prerequisites
- Flutter SDK installed
- Android emulator or physical device (for mobile testing)
- Or web browser (for web demo)

### Running the App

1. **For Android (Mobile)**:
   ```bash
   flutter run
   ```
   Select an Android device/emulator when prompted.

2. **For Web (Demo)**:
   ```bash
   flutter run -d chrome
   ```

3. **For Desktop**:
   ```bash
   flutter run -d windows
   ```

## Application Structure

### Main Components

- **Note Model**: Simple data class to store note content and metadata
- **NotesHomePage**: Main screen with input field and notes list
- **State Management**: Uses StatefulWidget for managing notes state

### Key Features Implemented

1. **Adding Notes**:
   - Enter text in the input field
   - Click "Save Note" button
   - Note appears in the list with timestamp

2. **Editing Notes**:
   - Click the edit icon (blue pencil) on any note
   - Note content loads into the input field
   - Make changes and click "Update Note"
   - Changes are saved with updated timestamp

3. **Deleting Notes**:
   - Click the delete icon (red trash) on any note
   - Confirmation dialog appears
   - Confirm deletion to remove the note

4. **UI Features**:
   - Clean Material Design interface
   - Responsive layout for mobile screens
   - Empty state when no notes exist
   - Cards for each note with proper spacing
   - Timestamp display for note creation

## Technical Details

- **Language**: Dart
- **Framework**: Flutter
- **State Management**: Built-in StatefulWidget
- **UI Components**: Material Design widgets
- **Data Storage**: In-memory list (resets on app restart)

## Screenshots

The app features:
- Blue app bar with "Notes App" title
- Text input area with save/update buttons
- Scrollable list of notes in card format
- Edit and delete icons for each note
- Confirmation dialogs for destructive actions