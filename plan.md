# Plan to Merge Features into `working_state.html`

This plan outlines the steps to integrate the "Courses" feature from `index_old.html` into `working_state.html`.

## Step 1: Add HTML for Courses Feature

- **Task 1.1:** Add the `courses-panel` placeholder div inside the header's right-side column.
- **Task 1.2:** Add the `course-detail-overlay` modal HTML structure at the end of the `<body>` tag, before the `<script>` tag.
- **Task 1.3:** Replace the "Activities" button in the footer with the "Add XP (Test)" button from `index_old.html`.

## Step 2: Add CSS for Courses Feature

- **Task 2.1:** Add the CSS rules for `#course-list-container`, `#course-detail-overlay`, and `#course-detail-content` to the `<style>` block in the `<head>`.

## Step 3: Integrate JavaScript Logic for Courses

- **Task 3.1: Update App State & Data:**
    - Add the `courses` data array.
    - Add the `currentCourse = null;` state variable.

- **Task 3.2: Add UI Element Selectors:**
    - Add the DOM element selectors for all course-related components and the `addXpButton`.

- **Task 3.3: Update Core Functions:**
    - Update `populateUI` to call the new `populateCourses` function.
    - Update `addEventListeners` to include listeners for the courses panel and the "Add XP" button.

- **Task 3.4: Add New Course-Related Functions:**
    - Add the `populateCourses()` function to generate the course list HTML.
    - Add the `toggleCoursesPanel()` function to handle showing/hiding the course list.
    - Add the `openCourseDetail()`, `closeCourseDetail()`, and `completeCourse()` functions to manage the course detail modal and its logic.

- **Task 3.5: Update `addXP` function:**
    - The `addXP` function in `index_old.html` is more complete. Replace the existing one with it.

## Step 4: Final Review and Cleanup

- **Task 4.1:** Review the merged `working_state.html` file for any inconsistencies or errors.
- **Task 4.2:** Ensure the welcome screen logic from `index_old.html` is NOT included. The loading screen from `working_state.html` should be used.
