# TaskMaster - Kanban Task Management App

A powerful, offline-capable Kanban board application for personal and business task management. Inspired by Trello, TaskMaster offers a clean dark-themed interface with comprehensive features for organizing your work.

![TaskMaster Screenshot](screenshot.png)

## Features

### Core Kanban
- **Multiple Boards** - Create, manage, and switch between unlimited boards
- **Drag & Drop Columns** - Reorder columns by dragging their headers
- **Drag & Drop Cards** - Move cards between columns with ease
- **Rich Card Details** - Title, description, due dates, priority, labels, and checklists

### Advanced Features
- **Calendar View** - Visualize tasks by due date in a monthly calendar layout
- **Recurring Tasks** - Set tasks to repeat daily, weekly, or monthly
- **File Attachments** - Attach and track local files to cards
- **Search & Filter** - Search by text, filter by priority, due date, and more
- **Archive System** - Archive completed cards without losing data
- **Board Templates** - Start quickly with pre-built templates

### Data Management
- **Local Storage** - All data stays on your machine
- **Auto-Save** - Changes saved automatically
- **Export/Import** - Backup and restore data as JSON
- **Backup Reminders** - Get reminded to backup your data

### UI/UX
- **Dark Theme** - Modern, eye-friendly dark interface
- **Responsive Design** - Works on desktop and mobile
- **Quick Add** - Rapidly add cards with keyboard shortcuts
- **Keyboard Shortcuts** - Efficient keyboard navigation

## Getting Started

### Installation

No installation required! TaskMaster is a single HTML file that runs in any modern web browser.

1. Save `index.html` to your computer
2. Double-click to open in your browser
3. Start organizing your tasks!

### Creating Your First Board

1. Click **+ New Board** in the header
2. Enter a name for your board
3. Choose a template:
   - **Blank** - Start fresh
   - **To Do** - Simple todo/done workflow
   - **Kanban** - Backlog, To Do, In Progress, Done
   - **Project** - Full project management pipeline
   - **Daily Routine** - Morning, Afternoon, Evening
   - **Content Plan** - Content creation workflow

## Using TaskMaster

### Managing Boards

- **Create Board**: Click "+ New Board" button or press `B`
- **Switch Board**: Use the dropdown in the top-left header
- **Delete Board**: Currently managed through board selection

### Working with Columns

- **Add Column**: Click the "+ Add Column" button at the end of your board or press `+`
- **Rename Column**: Click the pencil icon on the column header
- **Delete Column**: Click the trash icon (cards will be archived)
- **Reorder Columns**: Drag the column header to a new position

### Working with Cards

#### Creating Cards
- Click **"Add a card"** at the bottom of any column
- Use **Quick Add**: Press `N` and type your card title
- Specify column: Type `@columnname` in Quick Add (e.g., "Buy milk @todo")

#### Editing Cards
- Click any card to open the editor
- Available fields:
  - **Title** - Card name
  - **Description** - Detailed notes (supports multiline)
  - **Due Date** - When the task needs completion
  - **Priority** - Low, Medium, or High
  - **Recurring** - Repeat daily, weekly, or monthly
  - **Labels** - Color-coded tags
  - **Attachments** - Link to local files
  - **Checklist** - Subtasks with progress tracking

#### Card Features

**Priorities:**
- 🟢 Low - Minor importance
- 🟡 Medium - Normal priority
- 🔴 High - Urgent tasks

**Recurring Tasks:**
When you move a recurring task to another column, TaskMaster automatically creates the next occurrence:
- **Daily** - Creates same task for tomorrow
- **Weekly** - Creates task 7 days later
- **Monthly** - Creates task next month

**Checklists:**
- Add checklist items to break down tasks
- Check off items as you complete them
- Progress shown on card with "✓ X/Y"

**Attachments:**
- Click "Add File" to attach documents
- View and manage attachments in the card editor

#### Moving Cards
- **Drag and Drop**: Click and drag to move between columns
- **Keyboard**: Not yet supported (coming soon)

#### Archiving & Deleting
- **Archive**: Removes from board but keeps data (use "Archive" button in card editor)
- **Delete**: Permanently removes card (use "Delete" button in card editor)

### Calendar View

Switch to Calendar view to see all tasks with due dates:

1. Click the **Calendar** button in the header or press `C`
2. Navigate months with arrow buttons
3. Click "Today" to jump to current month
4. Click any task to open its details

Tasks are color-coded by priority in the calendar.

### Search & Filter

**Search Bar:**
- Type to search card titles across all columns
- Results update in real-time

**Filter Chips:**
- Click filter chips to show only matching cards:
  - 🔴 High Priority
  - 🟡 Medium Priority
  - 🟢 Low Priority
  - ⏰ Overdue
  - 📅 Due Today
- Click again to remove filter
- Multiple filters can be active at once

### Templates

Apply templates to existing boards:

1. Click the **Templates** button (📄)
2. Select a template:
   - **To Do List** - Simple list workflow
   - **Sprint Planning** - Agile development columns
   - **Bug Tracker** - Issue tracking workflow
   - **Goals** - Goal planning by timeframe

Template columns will be added to your current board.

### Archived Cards

View and restore archived cards:

1. Click **Archive** button (📦)
2. Browse archived cards
3. Click **Restore** to move back to board

### Data Management

#### Export Data
1. Open **Settings** (⚙️)
2. Click **Export Data (JSON)**
3. File downloads automatically

#### Import Data
1. Open **Settings**
2. Click **Import Data**
3. Select a previously exported JSON file
4. Confirm to replace current data

#### Backup
- Manual backup: Use Export feature
- Auto-reminders: Get notified if you haven't backed up in 7+ days
- Toggle reminders in Settings

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `N` | Quick Add Card |
| `B` | New Board |
| `C` | Toggle Calendar View |
| `+` | Add Column |
| `Ctrl/Cmd + K` | Focus Search |
| `?` | Show Help |
| `Esc` | Close Modal / Cancel |
| `Enter` | Submit / Save |

### Card Editing
- Click card to edit
- Tab between fields
- Enter to save checklist items

## Data Storage

TaskMaster stores all data in your browser's **LocalStorage**:

- **Location**: Browser local storage (not cookies)
- **Privacy**: Data never leaves your computer
- **Size Limit**: ~5-10MB depending on browser
- **Persistence**: Data remains until you clear browser data

### Backup Recommendations

Since data is local-only:

1. **Export weekly** - Keep a backup of your data
2. **Before browser updates** - Export as precaution
3. **Multiple devices** - Use import/export to sync

## Browser Compatibility

TaskMaster works in all modern browsers:

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## Tips & Tricks

### Workflow Ideas

**Personal Task Management:**
- Use Daily Routine template for habits
- Set recurring tasks for regular chores
- Use labels for categories (Work, Personal, Health)

**Project Management:**
- Use Kanban or Project template
- Assign priorities to manage workload
- Set due dates for milestones
- Use checklists for task breakdown

**Content Creation:**
- Use Content Plan template
- Track ideas through publication
- Attach files and resources
- Set publication dates

**Team Collaboration:**
- Share exported JSON files
- Use consistent naming conventions
- Archive completed work regularly

### Performance Tips

- Archive old cards to keep boards snappy
- Use search to find cards quickly
- Limit active filters for clarity
- Regular backups prevent data loss

## Troubleshooting

### Data Not Saving
- Check browser LocalStorage is enabled
- Ensure you haven't exceeded storage quota
- Try exporting and re-importing data

### Drag and Drop Not Working
- Ensure browser supports HTML5 drag API
- Try refreshing the page
- Check for JavaScript errors in console

### Import Fails
- Ensure file is valid JSON from TaskMaster export
- Check file isn't corrupted
- Try with a smaller test file first

### Calendar Not Showing Tasks
- Ensure tasks have due dates set
- Check you're viewing the correct month
- Verify tasks aren't archived

## Customization

TaskMaster uses CSS custom properties for theming. To customize:

1. Open `index.html` in a text editor
2. Find `:root` CSS variables
3. Modify colors to your preference
4. Save and refresh

## License

TaskMaster is free for personal and commercial use.

## Credits

Built with vanilla HTML, CSS, and JavaScript. No external dependencies required.

---

**Happy Task Managing!** 🚀
