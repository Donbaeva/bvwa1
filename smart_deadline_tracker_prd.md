# Smart Deadline Tracker - Product Requirements Document

## Project Overview
A modern web application for students to manage academic tasks, deadlines, and automate task entry via PDF import.

## Target Audience
University and high school students who need to organize homework, projects, exams, and personal obligations.

## Core Features

### 1. Task Management (CRUD)
*   **Add/Edit/Delete** tasks.
*   **Attributes**: Name, Description, Deadline (Date & Time), Priority, Category, Status (Done/Pending).
*   **Mark as Complete**: Toggle status easily.

### 2. Search & Filtering
*   **Search**: By task name.
*   **Filters**: All, Completed, Pending, Urgent (High Priority), Overdue.
*   **Sorting**: Sort by upcoming deadlines.

### 3. Dashboard & Statistics
*   Total tasks count.
*   Completed tasks count.
*   Overdue tasks count.
*   "Tasks for this week" view.

### 4. Countdown Timer
*   Visual countdown for each task (e.g., "2 days 5 hours remaining").

### 5. Personalization
*   **Dark / Light Mode**: User-selectable and persisted in localStorage.
*   **Categories**: School, Work, Personal, Visa, Exams.
*   **Priorities**: High, Medium, Low (color-coded).

### 6. PDF Import (Smart Feature)
*   Upload PDF files (syllabi, project requirements).
*   Automatic parsing of text to identify dates and task keywords.
*   Automatic creation of task entries from parsed data.

## Technical Stack
*   **Frontend**: HTML5 (Semantic), Tailwind CSS.
*   **Logic**: JavaScript (ES6+), PDF.js for parsing, Regex for date extraction.
*   **Storage**: localStorage for data persistence.

## Screen Map
1. **Dashboard**: High-level overview and stats.
2. **Tasks List**: The central hub for filtering and managing tasks.
3. **PDF Import**: Interface for uploading and confirming extracted tasks.
4. **Settings**: Theme toggle and category management.