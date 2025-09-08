# Website iCalendar Batch Generator

## Project Overview 
This tool provides users with a powerful and flexible way to batch-create iCalendar (.ics) files from various text-based formats or directly from schedule images. It is designed for efficiency, allowing users to quickly convert complex schedules into a universally importable calendar format. The image recognition functionality is powered by Google's Gemini Flash model.

## Quick Start

1. **Read CLAUDE.md first** - Contains essential rules for Claude Code
2. Follow the pre-task compliance checklist before starting any work
3. Use proper module structure under `src/main/js/`
4. Commit after every completed task

## Core Functionality
1. **Input**: A tabbed interface offering three distinct modes for creating events: Detailed Mode, Quick Scheduling Mode, and Image Import Mode.
2. **Detailed Mode**: Allows users to input a list of unique events, one per line. Each line is parsed individually, supporting different titles, times, locations, descriptions, and even recurring event rules.
3. **Quick Scheduling Mode**: Designed for events with a single, repeating title (like work shifts). The user inputs one title and then provides a list of dates and times in various flexible formats.
4. **AI-Powered Image Import**: Users can upload an image of a schedule. The AI returns structured JSON data containing all recognized events, which are then converted into an .ics file.

## Technology Stack
- **Frontend**: Single, self-contained HTML file
- **Styling**: Tailwind CSS via CDN
- **Language**: JavaScript (no external libraries for core functionality)
- **AI Integration**: Google Gemini Flash API for image understanding

## Universal Flexible Project Structure

**Standard Project Structure:** Full application structure with modular organization for scalable JavaScript development.

## Development Guidelines

- **Always search first** before creating new files
- **Extend existing** functionality rather than duplicating  
- **Use Task agents** for operations >30 seconds
- **Single source of truth** for all functionality
- **Language-agnostic structure** - works with JavaScript and other languages
- **Scalable** - start simple, grow as needed

## UI/UX Guidelines
**Theme**: Clean, professional design with user-selectable light and dark themes.
- **Light Mode**: White background (#FAFAFA), dark gray text (#1F2937), vibrant blue accent (#2563EB)
- **Dark Mode**: Dark slate background (#1c1c1c), light gray text (#D1D5DB), bright accent blue (#3B82F6)