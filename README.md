<!DOCTYPE html>
<html>
<head>
    <title>Victoria's Journal</title>
    <style>
        body {
            margin: 20px;
            padding: 20px;
            background-color: #d0ebe5;
            font-family: Arial, sans-serif;
        }

        #journal-container {
            border: 8px solid #b0e2d9;
            padding: 20px;
            width: 750px;
            margin: 0 auto;
            background-color: white;
            overflow: hidden; /* Ensures container wraps around floated elements */
        }

        /* Header / Title Box Styling */
        .header-box {
            background-color: #a2eae1;
            border: 2px solid #b2e4dc;
            padding: 15px;
            margin-bottom: 20px;
        }

        h1 {
            color: #ffffff;
            text-align: right;
            font-weight: bold;
            font-size: 26px;
            margin: 0;
        }

        .subtitle {
            display: block;
            text-align: right;
            color: #ffffff;
            font-style: italic;
            font-size: 13px;
            margin-top: 5px;
        }

        /* Sidebar Styling */
        .sidebar {
            float: left;
            padding: 15px;
            background-color: #a2eae1;
            color: white;
            width: 160px;
            border: 2px solid #b2e4dc;
            box-sizing: border-box;
        }

        .sidebar h2 {
            font-weight: normal;
            color: #ffffff;
            margin: 0 0 10px 0;
            font-size: 20px;
        }

        .sidebar ul {
            list-style-type: square;
            padding-left: 20px;
            margin: 0;
        }

        .sidebar li a {
            color: #00838f;
            text-decoration: underline;
            font-size: 13px;
            line-height: 1.8;
        }

        /* Main Content Area Styling */
        .content-area {
            float: right;
            width: 550px;
        }

        .entry-box {
            background-color: #e0f2f1;
            border: 2px solid #a2eae1;
            padding: 15px;
            margin-bottom: 20px;
            overflow: hidden; /* Clear floats inside entry */
        }

        .entry-title {
            color: #00838f;
            margin-top: 0;
            margin-bottom: 10px;
            font-size: 18px;
            font-weight: normal;
        }

        .date {
            text-decoration: underline;
        }

        .entry-box p {
            float: left;
            width: 360px;
            margin: 0;
            color: #555555;
            font-size: 12px;
            line-height: 1.4;
        }

        .entry-box img {
            float: right;
            width: 140px;
            height: 100px;
            object-fit: cover;
            border: 1px solid #cccccc;
        }

        .clear {
            clear: both;
        }
    </style>
</head>
<body>

<div id="journal-container">

    <!-- Header Box -->
    <div class="header-box">
        <h1>Victoria's Journal</h1>
        <span class="subtitle">So fresh and so clean</span>
    </div>

    <!-- Friends Sidebar -->
    <div class="sidebar">
        <h2>Friends</h2>
        <ul>
            <li><a href="#">albalove</a></li>
            <li><a href="#">big_bill</a></li>
            <li><a href="#">BarbaraFan</a></li>
        </ul>
    </div>

    <!-- Journal Entries Content Area -->
    <div class="content-area">
        
        <!-- Entry 1 -->
        <div class="entry-box">
            <h3 class="entry-title"><span class="date">04/09/08:</span> Spatulas</h3>
            <p>Yesterday, I went to the store and got some much-needed spatulas! What better way to say I love myself than to buy myself a spatula?</p>
            <img src="https://images.unsplash.com/photo-1590794056226-77ef3a6c4743?w=150" alt="Spatula"/>
        </div>

        <!-- Entry 2 -->
        <div class="entry-box">
            <h3 class="entry-title"><span class="date">04/08/08:</span> Cookie Cupcakes</h3>
            <p>My favorite cartoon character is Cookie, and my favorite dessert is cupcakes. So Cookie Cupcakes are best of both the worlds. Did you know Cookie Monster once said, "Sometimes me think what is love, and then me think love is what cookie is for." He gave up the last cookie for you. I wonder if the same applies for the cupcakes? If so, I don't think I can ever love ANYONE!</p>
            <img src="https://images.unsplash.com/photo-1576618148400-f54bed99fcfd?w=150" alt="Cookie Cupcakes"/>
        </div>

    </div>

    <div class="clear"></div>

</div>

</body>
</html>
"Added header styling and journal container"
