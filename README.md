<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<title>Notes Upload – Drishty Classes</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
    font-family: Arial;
    background:#f4f6f8;
    padding:20px;
}
.box{
    background:white;
    max-width:400px;
    margin:auto;
    padding:20px;
    border-radius:8px;
    box-shadow:0 2px 6px rgba(0,0,0,0.2);
}
h2{text-align:center;color:#2e7d32;}
input,button{
    width:100%;
    padding:10px;
    margin-top:10px;
}
button{
    background:#2e7d32;
    color:white;
    border:none;
    font-size:16px;
}
</style>
</head>

<body>

<div class="box">
<h2>📤 Notes Upload</h2>

<form action="https://docs.google.com/forms/d/e/FORM_ID/formResponse" method="POST" target="_blank">
    <input type="text" name="entry.1234567890" placeholder="Subject Name" required>
    <input type="text" name="entry.9876543210" placeholder="Google Drive File Link" required>
    <button type="submit">Submit</button>
</form>

<p style="font-size:13px;text-align:center;margin-top:10px;">
⚠️ File पहले Google Drive में upload करें
</p>
</div>

</body>
</html>
