# Sahara Connect - Tourism Platform Global Requirements

Create a modern SaaS tourism platform called "Sahara Connect" that connects tourists with local guides and experiences in Mauritania. This is a marketplace platform focusing on sustainable tourism and authentic cultural experiences.

## Technical Stack Requirements

- **Framework:** React 18+ with TypeScript
- **Styling:** Tailwind CSS (latest version)
- **Form Validation:** Zod for robust form validation
- **Data Fetching:** React Query (TanStack Query) for API requests and state management
- **Routing:** React Router DOM for navigation
- **Icons:** Lucide React for consistent iconography
- **Components:** Modular component architecture with proper separation of concerns

## Design & Branding Guidelines

### Color Palette & Theme

- **Primary Colors:** Warm desert-inspired palette with Sahara sunset colors
    - Golden amber (#F59E0B, #D97706)
    - Deep terracotta (#DC2626, #B91C1C)
    - Rich sand (#F3E8FF, #FEF3C7)
- **Secondary Colors:**
    - Oasis blue (#0EA5E9, #0284C7)
    - Palm green (#10B981, #059669)
- **Neutrals:** Modern grays (#F8FAFC to #1E293B)
- **Accent:** Vibrant sunset orange (#EA580C) for CTAs

### Visual Style

- **Aesthetic:** Modern, vibrant, and culturally respectful
- **Typography:** Clean, readable fonts with proper hierarchy
- **Imagery:** Desert landscapes, cultural elements, authentic experiences
- **Style:** Professional yet warm and inviting, reflecting Mauritanian hospitality

## Responsive Design Requirements

- **Mobile-First:** Optimized for mobile experience (320px+)
- **Tablet:** Enhanced layout for tablets (768px+)
- **Desktop:** Full-featured experience (1024px+)
- **Large Screens:** Optimized for 1440px+ displays
- **Touch-Friendly:** All interactive elements properly sized for touch

## Accessibility Standards

- **WCAG 2.1 AA Compliance:** Full accessibility compliance
- **Keyboard Navigation:** Complete keyboard accessibility
- **Screen Readers:** Proper ARIA labels and semantic HTML
- **Color Contrast:** Minimum 4.5:1 contrast ratio
- **Focus Indicators:** Clear focus states for all interactive elements
- **Alt Text:** Descriptive alt text for all images

## Architecture & Code Quality

- **Component Structure:** Each UI section as separate, reusable component
- **File Organization:** Logical folder structure (components/, pages/, hooks/, utils/)
- **TypeScript:** Strong typing throughout the application
- **Error Boundaries:** Proper error handling and user feedback
- **Loading States:** Skeleton loaders and loading indicators
- **Performance:** Optimized for fast loading and smooth interactions

## User Experience Priorities

- **Intuitive Navigation:** Clear, logical user flow
- **Fast Loading:** Optimized performance and perceived speed
- **Clear CTAs:** Obvious next steps and action buttons
- **Feedback:** Immediate response to user actions
- **Error Handling:** Helpful error messages and recovery options
- **Progressive Enhancement:** Works without JavaScript for core functions

## Platform Features Overview

This is a two-sided marketplace connecting:

- **Tourists:** Seeking authentic Mauritanian experiences
- **Local Guides:** Offering tours, cultural experiences, and expertise
- **Core Functions:** Browse experiences, book tours, manage itineraries, payments, reviews

## Component Architecture Guidelines

- Create separate components for each major UI section
- Use compound components for complex UI patterns
- Implement proper prop interfaces with TypeScript
- Follow React best practices (hooks, context when needed)
- Ensure each component is self-contained and reusable

## Initial Setup Request

Please create the foundational structure with:

1. Project setup with all required dependencies
2. Basic folder structure and component organization
3. Global styles and Tailwind configuration with the desert color palette
4. Main layout component with responsive navigation
5. Basic routing structure
6. TypeScript interfaces for core data types (User, Tour, Booking, etc.)
7. React Query setup for API calls
8. Basic loading and error components

Focus on creating a solid, scalable foundation that we can build upon. Make it visually appealing with the desert-inspired theme while maintaining professional standards and accessibility.

## Changes
### Internationalization
- Languages:
	- english
	- french
	- arab
- every component text must use ii8n
- every new component created must add their section in the ii8n for each language

### Requests
- the backend will be made with supabase
- for now mock them but use the fields of the form as guide for what will be the db structure
- create a service file with the code that will call the supabase api
- create a hook that uses this service
- enforce best practices on how to organize the code and files and directories