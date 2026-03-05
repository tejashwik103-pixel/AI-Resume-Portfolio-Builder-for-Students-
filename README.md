<!DOCTYPE html>
<html>
<head>
<title>AI Study Buddy</title>
<style>
body{
font-family: Arial;
text-align:center;
margin-top:100px;
background:#f2f2f2;
}

input{
width:400px;
padding:10px;
}

button{
padding:10px 20px;
background:blue;
color:white;
border:none;
}

.answer{
margin-top:20px;
background:white;
padding:20px;
width:500px;
margin-left:auto;
margin-right:auto;
}AI_Study_Buddy
│
├── app.py
│
└── templates
      │
      └── index.html
</style>
</head>app.py

<body>

<h1>AI Powered Study Buddy</h1>

<form method="POST">
<input type="text" name="question" placeholder="Ask your study question">
<button type="submit">Ask AI</button>
</form>

<div class="answer">
<p>{{answer}}</p>
</div>

</body>
</html>
