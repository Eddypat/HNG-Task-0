# HNG-Task-0

🚀 Stage 1 Updates - About & Contact Pages
I've successfully extended the Profile Card into a complete multi-page application with two new pages as required for Stage 1!

🆕 New Features Added
1. Multi-Page Navigation System
Navigation Bar with Home, About, and Contact links

Single-Page Application functionality using vanilla JavaScript

Active state highlighting for current page

Smooth transitions between pages

2. 📞 Contact Page (/contact)
Form with Complete Validation:

html

✅ All fields required

✅ Email format validation (name@example.com)

✅ Message minimum length (10 characters)

✅ Real-time validation on blur

✅ Error messages with proper ARIA attributes

✅ Success message after valid submission

✅ Form reset after successful submission

Accessibility:

♿ All inputs have proper <label> with for attributes

♿ Error messages linked with aria-describedby

♿ Keyboard navigable form

♿ Clear focus indicators

3. 👤 About Page (/about)

Content Structure:

Bio Section: Personal journey and background

Goals: Specific objectives for the Frontend Wizards program

Low Confidence Areas: Honest reflection on growth areas

Future Note: Motivational message to future self

Extra Thoughts: Additional insights and philosophy

4. 🔄 Preserved Stage 0 Features
✅ All original Profile Card functionality maintained

✅ Live time counter (milliseconds)

✅ Avatar upload feature

✅ Social media links with proper icons

✅ Responsive design for all screen sizes

✅ All original data-testid attributes preserved

🧪 Testing Ready
All required data-testid attributes are implemented:

Contact Page: 11 testable elements

About Page: 6 testable sections

Navigation: 2 testable elements

Profile Card: All original 8+ testable elements

🎯 Technical Implementation
No Frameworks Used:

Pure HTML5, CSS3, and Vanilla JavaScript

CSS Grid and Flexbox for layouts

CSS Custom Properties (variables) for theming

Mobile-first responsive design

JavaScript Features:

Page routing without page reloads

Form validation with real-time feedback

Dynamic error message display

Success state management

📱 Responsive Design
Breakpoints:

Mobile: < 576px (stacked layout)

Tablet: 576px - 767px

Desktop: ≥ 768px (side-by-side layouts)

♿ Accessibility Compliance
Semantic HTML throughout (main, section, nav, article)

ARIA labels and descriptions

Keyboard navigation support

Screen reader compatible

Color contrast compliance

🔄 How to Use the Updated Application
Navigation: Use the top navigation bar to switch between Home, About, and Contact pages

Contact Form: Fill out all required fields with valid data to see success message

Form Validation: Try submitting with empty fields to see error messages

Responsive Testing: Resize browser or view on different devices

📋 Acceptance Criteria Checklist
Contact Page ✅
All required fields with correct data-testids

Validation prevents invalid submissions

Success message shows after valid submission

Accessible form with labels and ARIA attributes

About Page ✅
All required sections with correct data-testids

Semantic HTML structure

Proper heading hierarchy

Reflective content in each section

General ✅
Semantic HTML throughout

Fully accessible

Responsive across all devices

Keyboard navigable

Clean, readable code
