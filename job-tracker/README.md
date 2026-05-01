# 🎯 Job Application Tracker

A React-based job application tracker that helps you manage your job applications and automatically matches them with your demo projects based on technology requirements.

## Features

- **Track Job Applications**: Add, edit, and delete job applications with details like company, position, status, and requirements
- **Manage Demo Projects**: Store your portfolio projects with technologies, demo URLs, and GitHub links
- **Automatic Project Matching**: The system automatically suggests which demo project to use based on matching technologies in job requirements
- **Status Tracking**: Track application status (To Apply, Applied, Interviewing, Offer, Rejected)
- **Persistent Storage**: All data is saved to localStorage, so your information persists across sessions
- **Responsive Design**: Works on desktop and mobile devices

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn

### Installation

1. Navigate to the project directory:
```bash
cd job-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## How to Use

### Adding Demo Projects

1. Click on the "Demo Projects" tab
2. Click "+ Add Project"
3. Fill in:
   - Project Name (required)
   - Description
   - Technologies Used (required) - List all technologies separated by commas
   - Demo URL (optional)
   - GitHub URL (optional)
4. Click "Add Project"

**Tip**: Be thorough when listing technologies - this is what the system uses to match jobs!

### Adding Job Applications

1. Click on the "Jobs" tab
2. Click "+ Add Job"
3. Fill in:
   - Company (required)
   - Position (required)
   - Job URL (optional)
   - Status
   - Date Applied
   - Requirements / Tech Stack - Paste the job requirements or list key technologies
4. The system will automatically suggest a matching demo project if one exists
5. Click "Add Job"

### Automatic Matching

When you enter job requirements, the system:
1. Scans all your demo projects
2. Looks for technology keywords that match
3. Displays the best matching project
4. Shows it prominently on the job card

This helps you quickly identify which demo project to showcase when applying!

### Updating Application Status

Use the status dropdown on any job card to update the application status as you progress through the hiring process.

## Data Storage

All data is stored in your browser's localStorage. This means:
- ✅ Your data persists between sessions
- ✅ No account required
- ✅ Fast and private
- ⚠️ Data is browser-specific (won't sync across devices)
- ⚠️ Clearing browser data will remove your information

## Tips for Job Hunting

1. **Keep Projects Updated**: Regularly add new projects and update technologies
2. **Be Specific with Requirements**: When adding jobs, include specific technologies mentioned in the job posting
3. **Use Multiple Tech Tags**: For projects, list all relevant technologies to increase match chances
4. **Track Everything**: Add every application to maintain a complete history
5. **Review Matches**: Always check the suggested demo project - it might remind you of a perfect project to highlight!

## Tech Stack

- React 18
- Vite
- CSS3 with Custom Properties
- LocalStorage API

## License

MIT - Feel free to use this for your job hunting!

---

Good luck with your job search! 🚀
