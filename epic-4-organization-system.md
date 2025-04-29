# Epic 4: Organization System

## Epic Description
As a GTD practitioner, I want to organize my clarified items into appropriate lists and categories so that I can view and access them in the most relevant contexts for taking action.

## User Stories

### Story 1: Next Actions Lists
**As a** user,  
**I want to** maintain context-based lists of next actions,  
**So that** I can see appropriate actions based on my current situation.

**Acceptance Criteria:**
- System provides default next action contexts (Calls, Computer, Errands, etc.)
- User can create custom context categories
- User can assign actions to multiple contexts if needed
- User can view all actions in a single list or filtered by context
- User can sort actions by priority, due date, energy level, or time required
- User can easily move actions between contexts
- System indicates when actions have dependencies on other actions

**Testing Criteria:**
- Verify default contexts are available and functioning
- Test creation of custom contexts
- Verify multi-context assignment
- Test all-actions view and context filtering
- Verify sorting functionality
- Test movement between contexts
- Verify dependency indicators

### Story 2: Projects List Management
**As a** user,  
**I want to** maintain a comprehensive list of all my projects,  
**So that** I can track all my open loops and active commitments.

**Acceptance Criteria:**
- System maintains a master list of all projects
- Projects automatically link to their associated next actions
- User can categorize projects by area of focus
- User can set project priorities
- User can add notes, resources, and planning details to projects
- User can see project status at a glance (active, on hold, completed)
- System indicates projects with no current next actions

**Testing Criteria:**
- Verify master project list functionality
- Test automatic linking to next actions
- Verify categorization by area of focus
- Test priority setting
- Verify addition of notes and resources
- Test status indicators
- Verify identification of projects without next actions

### Story 3: Waiting For Tracking
**As a** user,  
**I want to** track items I'm waiting for from others,  
**So that** I can follow up appropriately and ensure nothing falls through the cracks.

**Acceptance Criteria:**
- System maintains a dedicated Waiting For list
- Each waiting item includes who it was delegated to
- User can set expected completion dates for waiting items
- System provides overdue indicators for waiting items
- User can set reminders to follow up on waiting items
- User can add notes about waiting items
- User can convert waiting items to actions when follow-up is needed

**Testing Criteria:**
- Verify Waiting For list functionality
- Test delegation tracking
- Verify expected completion date setting
- Test overdue indicators
- Verify reminder functionality
- Test note-taking capability
- Verify conversion to action items

### Story 4: Calendar Integration
**As a** user,  
**I want to** see time-specific commitments in a calendar view,  
**So that** I can manage my hard landscape effectively.

**Acceptance Criteria:**
- System integrates with popular calendar applications (Google, Outlook, etc.)
- Calendar shows time-specific appointments and deadlines
- User can create new calendar items directly in the system
- User can set reminders for calendar items
- User can view calendar in day, week, and month formats
- Calendar distinguishes between appointments and day-specific deadlines
- User can see available time blocks for task completion

**Testing Criteria:**
- Test integration with calendar applications
- Verify display of time-specific items
- Test creation of new calendar items
- Verify reminder functionality
- Test different calendar views
- Verify distinction between item types
- Test available time block visualization

### Story 5: Reference Material Organization
**As a** user,  
**I want to** organize reference materials in an accessible system,  
**So that** I can quickly find information when needed.

**Acceptance Criteria:**
- System provides a dedicated reference section separate from action items
- User can create hierarchical categories for reference materials
- User can tag reference items with multiple keywords
- System provides full-text search of reference materials
- User can attach reference materials to projects and actions
- System supports various file types for reference materials
- User can quickly distinguish reference from actionable items

**Testing Criteria:**
- Verify separation from action items
- Test hierarchical category creation
- Verify multi-tag functionality
- Test search capabilities
- Verify attachment to projects and actions
- Test support for different file types
- Verify visual distinction from actionable items

### Story 6: Someday/Maybe List
**As a** user,  
**I want to** maintain a Someday/Maybe list,  
**So that** I can keep track of ideas and possibilities without cluttering my current actions.

**Acceptance Criteria:**
- System provides a dedicated Someday/Maybe section
- User can categorize Someday/Maybe items
- User can set reminders to review specific items
- System prompts for periodic review of Someday/Maybe list
- User can easily activate items by converting to projects
- User can add notes and context to Someday/Maybe items
- User can archive or delete items no longer of interest

**Testing Criteria:**
- Verify dedicated Someday/Maybe functionality
- Test categorization features
- Verify reminder setting
- Test periodic review prompts
- Verify conversion to active projects
- Test notes and context addition
- Verify archiving and deletion

### Story 7: Checklist Templates
**As a** user,  
**I want to** create and use checklist templates for recurring processes,  
**So that** I can ensure consistency and save time on repeated activities.

**Acceptance Criteria:**
- User can create checklist templates with multiple items
- User can organize templates by category
- User can generate new checklists from templates
- User can modify templates as processes evolve
- System tracks completion of checklist items
- User can share templates with other users
- System suggests templates based on past usage patterns

**Testing Criteria:**
- Test template creation
- Verify template organization
- Test generation of new checklists
- Verify template modification
- Test tracking of completion
- Verify template sharing
- Test suggestion algorithm

### Story 8: Areas of Focus 
**As a** user,  
**I want to** organize projects and actions by areas of responsibility,  
**So that** I can ensure balanced attention across all aspects of my life and work.

**Acceptance Criteria:**
- User can define personal areas of focus (e.g., Health, Finance, Career)
- User can define professional areas of responsibility
- User can assign projects to specific areas
- System shows distribution of active projects across areas
- User can view all actions related to a specific area
- System identifies areas with no active projects
- User can set target balance or priorities for different areas

**Testing Criteria:**
- Test definition of personal areas
- Verify definition of professional responsibilities
- Test project assignment to areas
- Verify distribution visualization
- Test area-specific action views
- Verify identification of inactive areas
- Test target balance setting

### Story 9: Project Support Materials
**As a** user,  
**I want to** organize supporting materials for my projects,  
**So that** I have everything I need when working on a project.

**Acceptance Criteria:**
- User can attach various types of materials to projects
- System organizes support materials by project
- User can add notes, links, and files to project support
- User can access project support materials when viewing project
- System distinguishes between reference materials and project support
- User can share project support materials with collaborators
- User can archive project support with completed projects

**Testing Criteria:**
- Test attachment of various material types
- Verify organization by project
- Test addition of notes, links, and files
- Verify access when viewing projects
- Test distinction from general reference
- Verify sharing capabilities
- Test archiving with completed projects

### Story 10: List Customization
**As a** user,  
**I want to** customize the appearance and behavior of my lists,  
**So that** they work in a way that matches my personal GTD practice.

**Acceptance Criteria:**
- User can customize list views (card, list, kanban, etc.)
- User can set default sorting for different list types
- User can customize fields displayed for each item type
- User can create saved filters and views
- System remembers user's preferred views for each list
- User can set color coding and visual indicators
- User can restore default settings if desired

**Testing Criteria:**
- Test different view options
- Verify default sorting options
- Test field customization
- Verify saved filters and views
- Test preference memory
- Verify color coding and indicators
- Test restoration of defaults