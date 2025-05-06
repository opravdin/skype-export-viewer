н# Skype Export Viewer

*[Русская версия](README.ru.md)*

A simple web-based viewer for Skype exported data that allows you to browse your conversations and media files.

## Overview

This tool provides a convenient way to view your exported Skype data, including:
- Text messages
- Images and videos
- Call history
- Group chat activities
- Polls and file shares

## How to Use

1. **Download your Skype data** from [https://secure.skype.com/en/data-export](https://secure.skype.com/en/data-export)
2. **Extract the ZIP file** to a folder on your computer
3. **Place the index.html file** from this repository into the same folder where you extracted your Skype data (necessary to show media preview)
4. **Open index.html** in your web browser
5. **Load messages.json** using the file picker at the top of the page

That's it! Your conversations will appear in the left sidebar. Click on any conversation to view its messages.

## Features

- Clean, intuitive interface
- Support for various message types (text, media, calls, etc.)
- Contact name resolution using the contacts.csv file
- Media viewer for images and videos
- Chronological message display
- Responsive design that works on different screen sizes

## Privacy Note

This viewer runs entirely in your browser. Your data is not uploaded to any server or shared with anyone. All processing happens locally on your computer.

## Technical Details

The viewer is fully vibe coded! It uses plain JavaScript and doesn't require any server-side processing. It parses the JSON data and displays it in a user-friendly format, resolving contact IDs to names when possible using the contacts.csv file.