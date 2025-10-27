# <ins>Category Two: Algorithms & Data Structures</ins>

The enhancement for the Algorithms & Data Structures category focused on how the app processes stored data and turns it into meaningful feedback for the user. The original version could record individual entries, but it didn’t really help the user understand trends. I added logic to calculate the average weight for each month and return those results in a form the rest of the app could display. The app can now show progress at the month level, not just at the single-entry level. 

<p align="center">
<img width="826" height="632" alt="Screenshot 2025-10-27 at 12 28 31 AM" src="https://github.com/user-attachments/assets/4ce0606c-cff4-4745-ae17-f5c6b31e3051" />
<br>
  <sub><strong>getMonthlyAverages() method that handles the weight averaging</strong></sub>
</p>

I also redesigned how the app builds the progress list on screen. Instead of just dumping all the entries one after another, the app now groups entries under month headers. As the list is built, the code detects when the month changes and inserts a header before continuing. This happens in one pass, so the app doesn’t need to repeatedly scan or sort during display. 

Another part of this enhancement was filtering and comparison logic. I added date-based filtering so the user can look at all data or narrow in on more recent ranges like the last 30 days or the last 7 days. Behind the scenes, the app calculates a cutoff date in ISO format and only returns entries on or after that point. On the home screen, I also added math to calculate recorded progress toward the user’s goal. The calculation is clamped so it always stays in a valid range and never shows impossible values. 

Sorting was also addressed. The user can now choose to see the newest entries first or flip that order to oldest first. I implemented a retrieval path that respects that choice directly, instead of forcing the app to manually reorder everything afterward. That keeps the flow predictable. It also avoids confusion when the user is trying to read their history in chronological order versus trying to see their most recent activity first.

**The following outcomes were met with these enhancements:**

I designed and evaluated computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution while managing the trade-offs involved in design choices by improving the logic that drives the app’s progress features. I wrote code that groups recorded entries by month, calculates an average for each month, and builds a structured view of progress over time. I also added filtering based on recent activity and a controlled way to sort results so the user can review either their latest changes or their longer-term trend.

I demonstrated an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals by turning raw stored data into something the user can understand and act on. These changes make the information more useful, because the app can now answer practical questions about progress instead of only displaying individual numbers.

