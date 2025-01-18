# User Manual for the Calendar and Event Management System

This manual provides an overview of the functionality and usage of the Calendar and Event Management System.

---

## **Features Overview**
1. **Interactive Calendar**  
   - Displays the current month, selectable days, and highlights the current day.
   - Allows navigation between months.
   - Enables event selection and display for specific days.

2. **Event Management**  
   - Create, modify, and delete events.
   - Mark events as completed.
   - Automatic categorization of events as "Pending," "Completed," or "Failed."

3. **Sidebar Navigation**  
   - Navigate between different sections (e.g., Home, About, Activity Summary).
   - Responsive design to hide/show the sidebar on smaller screens.

4. **Tables for Event Summaries**  
   - View all events, pending events, completed events, and failed events in separate tables.

5. **Dark Mode**  
   - Toggle between light and dark themes.

---

## **How to Use**

### **Calendar Navigation**
1. **Current Month Display**  
   - The current month and year are displayed at the top of the calendar.
2. **Change Month**  
   - Use the navigation buttons to move forward or backward through months.
3. **Day Selection**  
   - Click on any day in the calendar to view events for that date.

---

### **Event Management**

#### **Add an Event**
1. Fill out the following fields:
   - **Event Name**: Enter the name of the event.
   - **Start Time**: Specify the start time of the event.
   - **End Time**: Specify the end time of the event.
2. Click the **Add Event** button.
3. The event is added to the selected date and saved in local storage.

#### **Modify an Event**
1. Click the **Edit** (pen icon) button next to an event.
2. Enter the new details (event name, start time, and end time).
3. Ensure the start time is earlier than the end time.
4. The event is updated and re-sorted based on start time.

#### **Delete an Event**
1. Click the **Delete** (trash icon) button next to an event.
2. Confirm deletion. The event will be removed from the calendar.

#### **Mark an Event as Completed**
1. Click the **Mark Done** (checkmark icon) button next to an event.
2. Confirm the completion status.
3. The event will be marked as "Completed" and moved to the "Completed" table.

---

### **Event Categories**
1. **Pending Events**: Events that are upcoming or not yet marked as completed.
2. **Completed Events**: Events marked as completed by the user.
3. **Failed Events**: Events whose end time has passed and were not completed.

#### View Categories:
- Navigate to the respective sections to view categorized tables of events.

---

### **Sidebar Navigation**
1. **Home Button**  
   - Displays the main calendar interface.
2. **Activity Buttons**  
   - View total, completed, pending, and failed activities.
3. **About Button**  
   - Displays the "About" section of the app.

---

### **Responsive Design**
1. On devices with a screen width of less than 768px:
   - The sidebar is hidden by default.
   - Click the menu icon to toggle the sidebar visibility.

---

### **Dark Mode**
1. Use the dark mode toggle switch at the top of the screen.
2. Enable or disable dark mode as per your preference.

---

### **Technical Notes**
1. **Local Storage**  
   - All events are saved in the browser's local storage, ensuring persistence between sessions.
2. **Automatic Sorting**  
   - Events are sorted by their start time within each date.

---

## **Troubleshooting**
1. **Event Not Displaying**  
   - Ensure the event has a valid name, start time, and end time.
2. **Event Not Saving**  
   - Check that your browser supports local storage.
3. **Dark Mode Not Toggling**  
   - Ensure JavaScript is enabled in your browser.

---