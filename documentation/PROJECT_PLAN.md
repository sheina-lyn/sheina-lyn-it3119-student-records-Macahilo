# Student Records System

**Author or group:** Sheina Lyn Macahilo

**Section:** REPLACE WITH YOUR SECTION

**Problem:** Student records need a simple searchable course-based list.

**Users:** Approved class operators only.

**Features:** Sign in, list/search students, add, edit, delete, choose a course, show department, count students by course.

**Tables:** department, courses, students.

**Relationships:** department 1 to many courses; courses 1 to many students.

**Scope:** Synthetic records; shared operator access; email registration with instructor-approved records access.

**Lookup maintenance:** Department and course rows are managed in Supabase.

**Tests:** CRUD, relationships, constraints, report, trigger, denied access, and the same workflows on the deployed Vercel URL.