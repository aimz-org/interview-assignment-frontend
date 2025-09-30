# Interview Assignment: React TypeScript User Management Dashboard

## Overview
Your task is to build a modern React TypeScript application that creates a user management dashboard using the provided dataset. This assignment focuses on demonstrating your understanding of state management, UI/UX design principles, and TypeScript development skills.

## Dataset
The dataset (`data/mock_data.csv`) contains user information with the following fields:
- id
- first_name
- last_name
- email
- gender
- ip_address

## Technical Requirements

### 1. Technology Stack
- **React 18+** with TypeScript
- **Node.js** and **npm** for package management
- Use modern React patterns (functional components, hooks)
- Implement proper TypeScript typing throughout

### 2. Core Functionality

#### User Data Management
- Load and parse the CSV data into your application
- Display users in a well-designed table/list view
- Implement **search functionality** that filters users by:
  - First name
  - Last name
  - Email
  - Gender
- Add **pagination** or **virtual scrolling** for performance
- Implement **sorting** by any column

#### User Operations
- **Add new users** with form validation
- **Edit existing users** with pre-populated forms
- **Delete users** with confirmation
- **Bulk operations** (select multiple users for batch actions)

### 3. State Management Requirements
Demonstrate understanding of state management by implementing:
- **Local component state** for form inputs and UI interactions
- **Global state management** (choose one):
  - React Context + useReducer
  - Zustand
  - Redux Toolkit
  - Or any other modern state management solution
- Proper **state normalization** for user data
- **Optimistic updates** for better UX
- **Error state handling** throughout the application

### 4. UI/UX Requirements

#### Design System
- Use / Create a **consistent design system** with:
  - Color palette
  - Typography scale
  - Spacing system
  - Component variants
- Implement **responsive design**
- Use **modern CSS techniques** (CSS Grid, Flexbox, CSS Custom Properties)

#### User Experience
- **Loading states** for data operations
- **Error boundaries** with user-friendly error messages
- **Form validation** with clear feedback
- **Smooth animations** for state transitions

#### Suggested components to Build
- User table/card view with search and filters
- User form (create/edit) with validation
- Modal/dialog components
- Loading spinners and skeleton screens
- Toast notifications for user feedback
- Pagination controls

### 5. Advanced Features

#### Data Visualization
- Create **charts/graphs** showing user demographics
- Implement **data export** functionality (CSV, JSON)
- Add **statistics dashboard** with key metrics

#### Enhanced UX
- **Dark/light theme** toggle
- **Advanced filtering** with multiple criteria
- **User preferences** persistence (localStorage)
- **Keyboard shortcuts** for power users

#### Performance Optimization
- **Virtual scrolling** for large datasets
- **Debounced search** implementation
- **Memoization** of expensive calculations
- **Code splitting** and lazy loading

## Setup Instructions
1. Initialize a new React TypeScript project using `create-react-app` or `Vite`
2. Install necessary dependencies for state management and UI components
3. Set up your preferred styling solution (CSS Modules, Styled Components, Tailwind, etc.)
4. Implement the CSV data loader to parse the mock data
5. Build the application following the requirements above

## Evaluation Criteria
Your solution will be evaluated based on:

### Technical Skills
- **TypeScript proficiency**: Proper typing, interfaces, generics
- **React best practices**: Component design, hooks usage, performance
- **State management**: Clean architecture, proper data flow
- **Code organization**: Structure, readability, maintainability

### UI/UX Skills
- **Design quality**: Visual appeal, consistency, modern aesthetics
- **User experience**: Intuitive interactions, responsive design
- **CSS/HTML skills**: Modern techniques, clean markup

### Implementation Quality
- **Functionality completeness**: All requirements implemented
- **Error handling**: Robust error states and user feedback
- **Performance**: Efficient rendering, optimized operations
- **Documentation**: Clear README, code comments

## Bonus Points
- **Advanced animations**: Smooth micro-interactions
- **PWA features**: Service worker, offline capability
- **Advanced TypeScript**: Utility types, discriminated unions
- **Performance monitoring**: Bundle analysis, optimization

## Submission
Please provide:
1. **Repository link** with complete source code
2. **README** with:
   - Setup and running instructions
   - Features implemented
   - Technologies used
3. **Brief explanation** of your approach and any interesting challenges solved
