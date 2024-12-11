# Meeting Minutes - November 12th

## Conclusions

### Team Trust and Collaboration
1. **Decision-Making**:
   - Team members can propose suggestions, but the team lead (Haomin) will make the final decisions.
   - If product issues arise, Haomin will take primary responsibility.
   - In case of major conflicts:
     - Unless Haomin feels a meeting is necessary, he will make the final decision and bear the responsibility.
   - This approach is about improving team efficiency, not about individual capability differences.
   - Discussion with Kevin:
     - Confirm whether Kevin feels comfortable and aligned with this arrangement.

2. **Teamwork Principles**:
   - Team members should trust the team lead's decisions.
   - The team lead should respect and thoroughly consider team suggestions, maintaining open communication.
   - For major conflicts:
     - The team lead will take responsibility unless escalated to a team meeting.

---

## Technical Details

1. **Development Approach**:
   - Maintain a **fast iteration** rhythm during this stage.
   - Plan for dynamic requirement changes during development.

2. **Refactoring**:
   - Avoid unnecessary refactoring, but do not fear small-scale refactoring, especially in response to changing requirements.

3. **Decoupling**:
   - Apply decoupling appropriately and flexibly to prevent introducing new issues.

4. **MVP Design Philosophy**:
   - Focus on **business-oriented thinking (B2B)** rather than **customer-oriented (B2C)**.
   - Precision in design (e.g., pixel-perfect) is not necessary.
   - Prioritize core functionalities (e.g., filtering practitioners, booking appointments) with simplicity and usability over visual appeal.

5. **Figma Mockups**:
   - Primarily for the business team's demos; technical implementation does not need pixel-perfect alignment.
   - Focus on functionality over aesthetics.

6. **Responsive Web Development**:
   - Develop a single codebase compatible with both desktop and mobile.
     - Example:
       - Use `maxWidth: 400px` for login box width instead of `width: 400px` to ensure proper scaling.
       - For grids, define different column spans for various screen sizes (e.g., `md-6`, `xs-12`).

7. **UI and Component Libraries**:
   - Leverage component libraries; avoid custom CSS unless necessary.
   - This simplifies future updates (e.g., adding buttons, repositioning elements).
   - Most issues with component libraries stem from incorrect implementation. Following official documentation resolves 99% of problems.

8. **Avoid Code Duplication**:
   - Consolidate reusable CSS into a unified file (e.g., `w-100` for width: 100% or `flex-left-right-container`).
   - Add specific classes as needed (e.g., `w-100 user-input`).
   - For logic:
     - Avoid repetitive code.
     - Consolidate frequently copied logic into shared modules.

---

## Task Assignments

### **Haomin**:
1. Implement **Signup** and **Login**.
2. Develop practitioner backend **profile creation**.
3. Implement **Search** using MySQL full-text search with a dedicated search field.

### **Kevin**:
1. Refine **Figma mockups**.
2. Focus on the layout, specifically the **header design**.
