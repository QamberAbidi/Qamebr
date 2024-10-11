<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study Schedule - October 11th</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-image: url('https://source.unsplash.com/1600x900/?study,education,books,workspace,colorful');
            background-size: cover;
            background-position: center;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #fff;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
        }
        .schedule {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 20px;
            max-width: 600px;
            margin: auto;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }
        .time {
            font-weight: bold;
            color: #4CAF50;
        }
        .section {
            background-color: rgba(240, 240, 240, 0.9);
            border-left: 5px solid #4CAF50;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #45a049;
        }
        .details {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 20px;
            max-width: 600px;
            margin: 20px auto;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
        }
        .back-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
            transition: background-color 0.3s;
        }
        .back-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<h1>Study Schedule for October 11th</h1>

<div class="schedule">
    <div class="section">
        <span class="time">9:15 AM - 10:30 AM:</span>
        <button onclick="showDetails('detail1')" class="button">Details</button>
    </div>
    <div class="section">
        <span class="time">10:30 AM - 11:45 AM:</span>
        <button onclick="showDetails('detail2')" class="button">Details</button>
    </div>
    <div class="section">
        <span class="time">11:45 AM - 12:45 PM:</span>
        <button onclick="showDetails('detail3')" class="button">Details</button>
    </div>
    <div class="section">
        <span class="time">12:45 PM - 2:00 PM:</span>
        <button onclick="showDetails('detail4')" class="button">Details</button>
    </div>
    <div class="section">
        <span class="time">2:00 PM - 3:15 PM:</span>
        <button onclick="showDetails('detail5')" class="button">Details</button>
    </div>
    <div class="section">
        <span class="time">3:15 PM - 5:00 PM:</span>
        <button onclick="showDetails('detail6')" class="button">Details</button>
    </div>
</div>

<div id="detailsContainer" style="display:none;">
    <div id="detail1" class="details">
        <h2>Details for 9:15 AM - 10:30 AM</h2>
        <p>In this session, you will cover:</p>
        <ul>
            <li>Section 2: PEOPLE IN BUSINESS</li>
            <li>Topic:1 Organisational Structure</li>
            <li>Topic:2 Business Communication</li>
            <li>Topic:3 Leadership</li>
            <li>Topic:4 Human Resource Managment(HRM) Strategy</li>
        </ul>
        <p>Make sure to review your notes and relevant textbooks before this session.</p>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
    
    <div id="detail2" class="details" style="display:none;">
        <h2>Details for 10:30 AM - 11:45 AM</h2>
        <p>In this session, you will focus on:</p>
        <ul>
            <li>Section 3: MARKETING</li>
            <li>Topic:1 Marketing Analysis</li>
            <li>Topic:2 Sales Forcasting</li>
            <li>Topic:3 Marketing Strategy</li>
            <li>Topic:4 International Marketing</li>
        </ul>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
    
    <div id="detail3" class="details" style="display:none;">
        <h2>Details for 11:45 AM - 12:45 PM</h2>
        <p>This session will involve:</p>
        <ul>
            <li>Business Studies 9609 Past Paper</li>
            <li>-May June 2023 Paper 31</li>
        </ul>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
    
    <div id="detail4" class="details" style="display:none;">
        <h2>Details for 12:45 PM - 2:00 PM</h2>
        <p>Focus on:</p>
        <ul>
            <li>Section 4:OPERATIOON MANAGEMENT</li>
            <li>Topic 1: Location and Scale</li>
            <li>Topic 2: Technology and Innovation</li>
            <li>Topic 3: Quality management</li> 
            <li>Topic 4: Lean production</li>
            <li>Topic 5: Project management</li>
        </ul>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
    
    <div id="detail5" class="details" style="display:none;">
        <h2>Details for 2:00 PM - 3:15 PM</h2>
        <p>In this session:</p>
        <ul>
            <li>Secton 5: FINANCE AND ACCOUNTING </li>
            <li>Topic 1: Financial Statements</li>
            <li>Topic 2: Ratio Analysis</li>
            <li>Topic 3: Investment appraisa</li>
        </ul>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
    
    <div id="detail6" class="details" style="display:none;">
        <h2>Details for 3:15 PM - 5:00 PM</h2>
        <p>Covering:</p>
        <ul>
            <li>BUSSINESS AND IT'S ENVIRONMENT</li>
            <li>Topic 1: External Influences</li>
            <li>Topic 2: Economic Influences</li> 
            <li>Topic 3: Business Strategy</li>
        </ul>
        <button onclick="hideDetails()" class="back-button">Back to Schedule</button>
    </div>
</div>

<footer>
    Good luck with your studies!
</footer>

<script>
    function showDetails(detailId) {
        document.getElementById('detailsContainer').style.display = 'block';
        var details = document.querySelectorAll('.details');
        details.forEach(function(detail) {
            detail.style.display = 'none';
        });
        document.getElementById(detailId).style.display = 'block';
    }

    function hideDetails() {
        document.getElementById('detailsContainer').style.display = 'none';
    }
</script>

</body>
</html>

