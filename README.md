# Assignment
Frontend Engineer Take-Home Task: Building a Resume Experience Editor

# Frontend Engineer Take-Home Task: Building a Resume Experience Editor

## Objective
Create a component for editing resume experience entries, similar to modern resume builders. The component should allow users to add, edit, and format their work experience descriptions.

## Core Requirements

### 1. Experience Entry Editor
* Display experience entry fields:
  - Company name
  - Job title
  - Location (city)
  - Country
  - Start date and end date
  - "I currently work here" checkbox
  - Description with rich text formatting

### 2. Rich Text Editor for Description
* Implement basic text formatting options:
  - Bold
  - Italic
  - Underline
  - Bullet points
  - Numbered lists
* Format buttons should appear in a toolbar above the description field

### 3. Entry Management
* Allow adding new experience entries
* Implement collapse/expand functionality for each entry
* Allow deleting experience entries
* Ability to reorder entries (optional bonus)

### Technical Requirements
* Use Next.js 14+ with App Router
* Implement using TypeScript
* Use TailwindCSS for styling
* Store data in local state (no backend required)

## Provided Resources
In the starter repository:
* `sample-experience.json` - Sample experience entries data
* TypeScript interfaces for the data structure
* Basic project setup with Next.js, TypeScript, and TailwindCSS

## Submission Requirements
* GitHub repository with your solution
* README with setup instructions
* Deployed version using Vercel

## Evaluation Criteria
1. **Functionality (40%)**
   - Working rich text editor
   - Proper handling of experience entries
   - Smooth add/edit/delete operations

2. **Code Quality (40%)**
   - Clean, maintainable code
   - TypeScript usage
   - Component organization

3. **User Experience (20%)**
   - Intuitive interface
   - Working formatting controls
   - Proper error handling

## Time Expectation
* You have 2 days to complete this task
* We expect it would take approximately 6-8 hours of focused work

## Sample Data Structure
```typescript
interface ExperienceEntry {
  id: string;
  company: string;
  title: string;
  location: string;
  country: string;
  startDate: string;
  endDate: string | null;
  currentlyWorking: boolean;
  description: string; // Can contain HTML for rich text
}
```

## Notes
* You can use libraries like Slate.js, TipTap, or Draft.js for the rich text editor
* Focus on making the editing experience smooth and intuitive
* Reach out if you need clarification on requirements

The goal is to create a focused, well-implemented component that handles experience entry editing effectively.

