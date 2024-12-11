# Platform Modification Suggestions - February 23, 2024

## Mid-Week Test Review – Hao Min

---

## Service and Description Design

1. **Page Layout**:
   - **Left Side**:
     - Background
     - Experience
     - Education
   - **Right Side**:
     - Add a "Book" button that directly leads to the monthly calendar (skip the weekly calendar).

2. **Service Functionality**:
   - Add "Book" and "Add to Wishlist" (with a red heart icon) for each service.
   - During checkout, display the service name at the top of the page.

---

## Mentor Pricing Adjustments
1. **Suggested Price Adjustments**:
   - Change mentor-recommended prices:
     - `$72.3 → $74.9`
     - `$76.5 → $79.9`
2. **Actual Prices**:
   - Allow mentors to adjust their prices up or down, rounded to the nearest $5 increment.

---

## Resume Services
1. **Pricing Display**:
   - For resume editing services, display only the price for 500 words.
   - Add an `i` icon for price explanation (hover to view details for additional word costs).

2. **Checkout Page**:
   - Add the following below the upload section:  
     "*You can also choose the resume from Cospace.*"

3. **Upload Interface**:
   - Display a dashed box in the center of the upload interface.
   - After uploading, display the file name and format.
   - For resumes uploaded from Cospace, replace the "Check" button with an "Upload" button.
   - If no resume is uploaded, the "Next" button should be greyed out.

4. **Data Storage**:
   - Ensure uploaded resumes are stored both in the platform's database and in Cospace.

---

## Booking and Cospace
1. **Interface Merge**:
   - Combine "My Schedule" and "Cospace" into a single section: **Booking & Cospace**.

2. **Mentor Rejection Feature**:
   - Add a function that allows mentors to reject bookings.
   - If a mentee has already paid and the mentor rejects the booking, refund the payment to the mentee immediately.
