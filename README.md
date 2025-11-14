# busy-day
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Busy Day Schedule</title>
  <style>
    /* Style for the overall table */
    table {
      width: 60%;
      border-collapse: collapse;
      margin: 40px auto;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f7f9fa;
      box-shadow: 0 4px 16px rgba(0,0,0,0.09);
    }

    /* Style for the table headers */
    th {
      background-color: #3f51b5;
      color: #fff;
      font-size: 1.15em;
      padding: 14px 0;
      border-bottom: 2px solid #283593;
      letter-spacing: 0.5px;
    }

    /* Style for all table cells */
    td {
      border-bottom: 1px solid #e0e4ea;
      padding: 12px;
      text-align: center;
      font-size: 1em;
      color: #222;
      background-color: #fff;
    }

    /* Style for the entire first column (time) */
    td.time-col {
      background-color: #e3f2fd;
      font-weight: bold;
      color: #1976d2;
      width: 120px;
    }

    /* Highlight a specific entire row (for example, Lunch Break) */
    tr.lunch-row {
      background-color: #ffe082 !important;
    }

    /* Add a border and a slight radius to the whole table */
    table {
      border: 2px solid #3f51b5;
      border-radius: 10px;
      overflow: hidden;
    }

    /* Add hover effect on rows */
    tbody tr:hover {
      background-color: #e3f1fc;
    }

    /* Style a specific table header (Event) */
    th.event-header {
      background-color: #7986cb;
    }
  </style>
</head>
<body>
  <h2 style="text-align:center; color:#3f51b5;">Online Schedule App: A Busy Day</h2>
  <table>
    <thead>
      <tr>
        <th>Time</th>
        <th class="event-header">Event</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">6:30 AM</td>
        <td>Wake Up &amp; Morning Stretch</td>
      </tr>
      <tr>
        <td class="time-col">7:00 AM</td>
        <td>Make &amp; Eat Breakfast</td>
      </tr>
      <tr>
        <td class="time-col">8:00 AM</td>
        <td>Walk the Dog</td>
      </tr>
      <tr>
        <td class="time-col">9:00 AM</td>
        <td>Team Standup Zoom Meeting</td>
      </tr>
      <tr>
        <td class="time-col">10:30 AM</td>
        <td>Client Emails &amp; Project Tasks</td>
      </tr>
      <tr class="lunch-row">
        <td class="time-col">12:00 PM</td>
        <td>Lunch Break (Chicken Salad &amp; Read News)</td>
      </tr>
      <tr>
        <td class="time-col">1:00 PM</td>
        <td>Grocery Shopping</td>
      </tr>
      <tr>
        <td class="time-col">2:30 PM</td>
        <td>Code Review for Online Schedule App</td>
      </tr>
      <tr>
        <td class="time-col">4:00 PM</td>
        <td>Doctor's Appointment</td>
      </tr>
      <tr>
        <td class="time-col">6:00 PM</td>
        <td>Dinner with Family</td>
      </tr>
      <tr>
        <td class="time-col">8:00 PM</td>
        <td>Online Yoga Class</td>
      </tr>
      <tr>
        <td class="time-col">9:30 PM</td>
        <td>Plan Next Day &amp; Relax</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
