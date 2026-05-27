# Team Task Tracker

A free, collaborative task management app for Google Workspace teams with Google Drive integration.

## Features

✅ **Add & Manage Tasks** - Create tasks with deadlines, priorities, and team assignments  
✅ **Real-time Sync** - All tasks automatically sync to Google Drive  
✅ **Team Dashboard** - See task counts for each team member  
✅ **Smart Filtering** - Filter by All, Active, Completed, or Overdue tasks  
✅ **Deadline Tracking** - Visual indicators for overdue and upcoming tasks  
✅ **No Setup Required** - Just sign in with Google and start managing tasks  

## Getting Started

1. Visit: `https://josetorrestevas.github.io/task-tracker/task_tracker.html`
2. Click **Sign in with Google**
3. Authenticate with your Google account
4. Start adding tasks!

## Setup Instructions for Developers

### Prerequisites
- Google Cloud Project with Drive and Sheets APIs enabled
- OAuth 2.0 credentials (Client ID and API Key)

### Installation

1. Clone the repository
2. Open `task_tracker.html` in a text editor
3. Replace these lines with your Google credentials:
```javascript
   const CLIENT_ID = 'YOUR_CLIENT_ID_HERE';
   const API_KEY = 'YOUR_API_KEY_HERE';
```
4. Save the file
5. Upload to GitHub Pages or host on any web server

### Google Cloud Setup

1. Create a Google Cloud Project
2. Enable Google Drive API and Google Sheets API
3. Create OAuth 2.0 credentials (Web application)
4. Add authorized origins:
   - `https://josetorrestevas.github.io`
5. Add authorized redirect URIs:
   - `https://josetorrestevas.github.io/task-tracker/`

## How It Works

- **First user** signs in and creates a Google Sheet called "WorkspaceTaskTracker"
- **All tasks** are stored in that Google Sheet
- **Team members** can sign in and see/edit the same tasks
- **Real-time sync** - Changes save instantly to Google Drive

## Sharing Tasks with Your Team

1. First person creates tasks (Google Sheet is created automatically)
2. Go to Google Drive and find "WorkspaceTaskTracker" spreadsheet
3. Click **Share** and add team members' emails
4. They can now sign in and see the same tasks

## Tech Stack

- HTML5 + CSS3 + JavaScript
- Google Drive API
- Google Sheets API
- Google Identity Services

## License

Free to use and modify for your team.

## Questions?

Create an issue on GitHub or reach out to the repository owner.
