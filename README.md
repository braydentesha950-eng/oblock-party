<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>THE OBLOCK PARTY</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#111;
    color:white;
}

.hero{
    text-align:center;
    padding:50px 20px;
    background:linear-gradient(to right,#000,#222);
}

.hero h1{
    font-size:3rem;
    color:#ffb300;
}

.hero p{
    margin-top:10px;
    font-size:1.2rem;
}

.section{
    padding:40px 20px;
    max-width:1000px;
    margin:auto;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:15px;
}

.card{
    background:#222;
    padding:20px;
    border-radius:10px;
    text-align:center;
}

.ticket{
    background:#ffb300;
    color:black;
    padding:20px;
    border-radius:10px;
    margin-bottom:15px;
}

form{
    display:flex;
    flex-direction:column;
    gap:10px;
}

input,select{
    padding:12px;
    border:none;
    border-radius:6px;
}

button{
    background:#ffb300;
    border:none;
    padding:12px;
    border-radius:6px;
    font-size:16px;
    cursor:pointer;
}

footer{
    text-align:center;
    padding:20px;
    background:#000;
}
</style>
</head>

<body>

<div class="hero">
    <h1>THE OBLOCK PARTY</h1>
    <p>Ubungo • 20/06/2026 • From 13:00 Till Late</p>
</div>

<div class="section">
    <h2>Services Available</h2>
    <br>

    <div class="cards">
        <div class="card">🎵 Unlimited Music</div>
        <div class="card">📶 Free WiFi</div>
        <div class="card">🍔 Food & Drinks</div>
        <div class="card">🎧 DJ Presence</div>
        <div class="card">💨 Shisha</div>
    </div>
</div>

<div class="section">
    <h2>Tickets</h2>
    <br>

    <div class="ticket">
        <h3>Single Ticket</h3>
        <h1>15,000 TZS</h1>
    </div>

    <div class="ticket">
        <h3>Double Ticket</h3>
        <h1>25,000 TZS</h1>
    </div>
</div>

<div class="section">
    <h2>Payment Details</h2>
    <br>

    <p><strong>Mixx by Yas</strong></p>
    <p>Account Name: THE OBLOCK PARTY</p>
    <p>Lipa Number: 46148895</p>

    <br>

    <p>After payment fill the form below.</p>
</div>

<div class="section">
    <h2>Book Your Ticket</h2>
    <br>

    <form>
        <input type="text" placeholder="Full Name" required>
        <input type="tel" placeholder="Phone Number" required>

        <select required>
            <option>Select Ticket Type</option>
            <option>Single - 15,000 TZS</option>
            <option>Double - 25,000 TZS</option>
        </select>

        <input type="file">

        <button type="submit">
            Submit Booking
        </button>
    </form>
</div>

<footer>
    Contact: 0691033223
</footer>

</body>
</html>![1001148652](https://github.com/user-attachments/assets/5421eeb6-fbc4-4a57-9566-fda7d6dd52bf)
