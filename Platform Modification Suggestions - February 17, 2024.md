# Platform Modification Suggestions - February 17, 2024

## General UI Adjustments
1. **Callmentor Logo**:
   - Reduce the size of the Callmentor icon.
   - Make the font on the logo smaller.
   - Display a clickable hand icon when the mouse hovers over the logo.

2. **Search Bar**:
   - Use a rounded rectangular shape for the search bar.
   - Ensure the search bar is fully utilized without blank spaces.
   - Leave more space between the icon and the search bar.

3. **Calendar**:
   - Reference Expedia for the design.
   - Combine "Start" and "End" in one field, separated by a straight line.

---

## Search Functionality
1. **Date Selection**:
   - Disable date selection for past days.
   - Allow searches without selecting a date, but only show services available from today onward.

2. **Search Results**:
   - Remove the secondary search interface.
   - Search filters should include:
     - Location
     - Job Title
     - Company
     - Price
   - Clicking the image in search results should lead directly to the service page (no image zoom).
   - Disable full-text popups when hovering over service descriptions.

---

## Service Page
1. **Job Title**:
   - Optionally include a "Level" field (e.g., Senior, Junior) after the Job Title.
2. **Calendar Adjustments**:
   - Show only weeks and months, not individual days.
   - For weeks and months:
     - Display only the month name above the calendar (e.g., "February 2024," not "2024-02").
     - Weekly calendars should run from Monday to Sunday.
     - Remove the "All Day" row.
     - Display the full week without horizontal scrolling.
     - Format days as "Sun 11, Mon 12" (not "11 Sun, 12 Mon").
   - Differentiate services by day with clear dividers in the calendar.
   - Clicking a service or date in the monthly calendar should navigate to the weekly calendar.
3. **Time Selection**:
   - Allow users to select start times using hour and minute dropdowns.
   - Only display available times for selection based on mentor availability.
4. **Cart and Orders**:
   - Add a "Buy Now" button below "Add to Cart."
   - Show a larger "Added to Cart successfully!" message after adding to the cart.
   - Disable the "Place Order" button if the cart is empty or grey it out.
   - After placing an order, display "Go prepare for your meeting" (no punctuation).

---

## Login and Registration
1. **When Not Logged In**:
   - Show a login screen when "My Schedule" is clicked, with a "Sign in or create a free account" button.
2. **Registration**:
   - Add automatic email detection for student email addresses. Show an error for non-student emails.
3. **Error Handling**:
   - Replace "Internal server error" messages with user-friendly prompts.

---

## Meeting Preparation
1. **File Uploads**:
   - Directly upload files without redundant confirmation screens.
   - Add a "Delete" function for uploaded files.
   - Do not send Google Drive links to mentees after uploads.
   - Filter inappropriate images or restrict file formats.
2. **Save Functionality**:
   - After saving, grey out the "Save" button.
   - Re-enable the "Save" button if comments are changed.

---

## Meetings
1. **Join Meeting**:
   - Limit entry to meetings to 5 minutes before the start time.
   - Add a full-screen option.
   - Update the bottom toolbar:
     - Add: Chat, Raise Hand, Background Blur.
     - Remove: Security (what is its function?).
2. **View & Edit Meeting**:
   - Replace "Order Number" with "Order Placed" and the order date (e.g., "Order Placed February 17, 2024").
   - Add a "Cancel" button in the first step with the cancellation policy.
   - If canceled, display "Cancelled" in the second step.
3. **Meeting Status**:
   - Move completed meetings to "Past" immediately after the scheduled end time.

---

## Mentor Registration
1. **Personal Information**:
   - Allow users to select from a dropdown list or manually input details.
2. **Tab Navigation**:
   - Ensure smooth transitions between registration tabs.

---

These changes aim to enhance usability, streamline navigation, and improve the overall user experience on the Callmentor platform.
