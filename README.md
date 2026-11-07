# Social Media Client Manager

A solo GoMyCode Lab Phase project by Marvin Simon.

## Project topic
A web application for organising social media clients, planning content and recording campaign results in one place.

## Why this project
Managing content for different clients means keeping track of brand details, captions, deadlines and published posts. This application will bring those tasks into a clear dashboard. The idea draws on my work in social media management.

## Planned features
- Dashboard showing client totals and posts by status.
- Add, view, edit and delete clients.
- Create content plans with a client, platform, caption and planned publication date.
- Update content status: Draft, Ready or Published.
- Search and filter content by client, platform and status.
- Record campaign results manually, including reach, likes, comments and clicks.
- Responsive layout for desktop and mobile.
- Account login and private records for each user.

The initial version will organise content; it will not automatically publish to social platforms or fetch analytics.

## Technologies
- Frontend: React with Vite, JavaScript and CSS.
- Backend: Node.js and Express.
- Database: MongoDB with Mongoose.
- Tools: VS Code, Git Bash, Git, GitHub and npm.

## Implementation approach
Use React components, useState for form and application state, useEffect for API loading, and ordinary functions for event handlers. Express routes will handle requests and validate input. Mongoose models will describe users, clients and posts. Keep the code readable and introduce each feature in small steps.

## Main screens
1. Login and registration.
2. Dashboard with summary cards and upcoming content.
3. Clients with an add/edit form.
4. Content planner with search, filters and status controls.
5. Campaign results with manually entered metrics.

## Development stages
1. Confirm project scope with the instructor and sketch the screens.
2. Create the React/Vite project and build the responsive interface with sample data.
3. Implement client and content forms, editing, deletion, search and filters.
4. Build Express routes and connect MongoDB.
5. Add authentication and ensure users can access only their own records.
6. Validate main workflows, fix layout issues and document deployment.

## Acceptance checks
- Client and post changes persist in MongoDB.
- Required fields show helpful errors.
- Search, filters and status changes work together.
- Private records cannot be read or changed by another account.
- The interface remains usable on narrow screens.
- README instructions match the implemented application.

## Current status
Project proposal only. Implementation and instructor approval are pending. No live deployment or completed feature is claimed.
