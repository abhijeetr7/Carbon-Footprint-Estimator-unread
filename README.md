# Carbon-Footprint-Estimator-unread

This application provides a user-friendly interface to estimate your carbon footprint based on common habits.

Here's a summary of the features:

Intuitive UI: A clean and responsive design using Tailwind CSS for easy input.

Daily/Weekly/Monthly Toggle: Adjusts the calculation based on your preferred time period.

Comprehensive Input Fields: Covers travel (car, plane, public transport), food (diet type), and energy (electricity, natural gas).

Emission Formula Logic: Calculates the estimated CO2e based on predefined emission factors.

Real-time Saving and Comparison: Integrates with Firestore to save your footprint data and display a history of your progress. Your data is stored privately under your unique user ID.

User ID Display: Shows your unique user ID, which is important if you want to share or compare data in a multi-user context (though this app focuses on individual tracking).

Notifications: Provides clear messages for successful saves or errors.

This updated Canvas now includes:

Carbon Footprint Trend Chart: A line chart powered by Chart.js is added to the "Saved Progress" section. It visualizes your saved carbon footprints over time, allowing for a quick overview of your impact trends.

Edit Functionality: Each saved entry now has an "Edit" button. Clicking this button populates the input fields with the data from that specific entry, and the "Save Progress" button changes to "Update Entry". You can then modify the values and click "Update Entry" to save changes to the existing record.

Cancel Edit Button: A "Cancel Edit" button appears when you are in editing mode, allowing you to discard changes and revert the form to its default state.

These enhancements make the Carbon Footprint Estimator more robust for tracking and managing your environmental impact data.
