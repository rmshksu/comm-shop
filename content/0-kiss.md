---
title: Keep It Simple, Stupid!
nav: K-I-S-S
---

>“Don’t talk to the general audience as you would your scientific colleagues. There are terms that convey your meaning instantly and accurately to fellow experts. You may parse these phrases every day in your professional work. But they do no more than mystify an audience of non-specialists. Use the simplest possible language. Above all, remember how it was before you, yourself, grasped whatever it is you’re explaining.” - Carl Sagan

-------------

{% capture text %}
Nobody wants to listen to a lecture when they were expecting a sales pitch.

Nobody's excited when a quick description becomes a novel.

Keep it simple, stupid.
{% endcapture %}
{% include alert.html text=text color=secondary %}

<br>

<html>
<head>
<style>
table {
  width: 30%; /* smaller width */
  border-collapse: collapse;
  margin: 10px 0; /* smaller margin */
  font-size: 14px; /* smaller text */
}
th, td {
  border: 1px solid #ddd;
  padding: 4px; /* smaller padding */
  text-align: center;
}
th {
  background-color: #f4f4f4;
  font-weight: bold;
}
tr:nth-child(even) {
  background-color: #f9f9f9;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Symbol</th>
    <th>Associated Feeling</th>
  </tr>
  <tr>
    <td>N</td>
    <td>Neutral</td>
  </tr>
  <tr>
    <td>+</td>
    <td>Positive</td>
  </tr>
  <tr>
    <td>-</td>
    <td>Negative</td>
  </tr>
</table>

</body>
</html>

## Start at the End, **What do you want?**

<html>
<head>
<style>
.block-container {
  display: flex;
  align-items: center;
  background-color: #f9f9f9;
  border: 2px solid #ccc;
  border-radius: 8px;
  padding: 20px;
  margin: 20px 0;
}

.plus-box {
  flex-shrink: 0;
  width: 80px;
  height: 80px;
  background-color: #e0e0e0;
  color: #333;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 48px;
  font-weight: bold;
  border-radius: 10px;
  margin-right: 20px;
}

.text-content {
  font-size: 18px;
  line-height: 1.4;
}
</style>
</head>

<body>

<div class="block-container">
  <div class="plus-box">+</div>
  <div class="text-content">
    I want everyone in the crowd to recognize:  
    Learning isn't about getting the right answer.  
    It's about failing until you understand.
  </div>
</div>

</body>
</html>


<br>

## Trim the Fat, **What are you really saying?**

<html>
<head>
<style>
table {
  width: 80%;
  border-collapse: collapse;
  margin: 20px 0;
  font-size: 16px;
}
th, td {
  border: 1px solid #ddd;
  padding: 10px;
  vertical-align: middle;
  text-align: left;
}
th {
  background-color: #f4f4f4;
  font-weight: bold;
}
tr:nth-child(even) {
  background-color: #f9f9f9;
}
.symbol-box {
  display: inline-block;
  width: 30px;
  height: 30px;
  border: 2px solid #333;
  border-radius: 5px;
  text-align: center;
  line-height: 28px;
  font-weight: bold;
  margin-right: 10px;
}
.highlight {
  color: #007BFF; /* bright blue */
  font-weight: bold;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Symbol</th>
    <th>Message</th>
  </tr>
  <tr>
    <td><div class="symbol-box">N</div></td>
    <td>I want everyone in the crowd to recognize</td>
  </tr>
  <tr>
    <td><div class="symbol-box">+</div></td>
    <td><span class="highlight">Learning</span> isn't about getting the right answer</td>
  </tr>
  <tr>
    <td><div class="symbol-box">-</div></td>
    <td><span class="highlight">It's about failing until you understand</span></td>
  </tr>
</table>

</body>
</html>


<div style="text-align: center; font-size: 28px; font-weight: bold; margin: 20px 0;">
Learning. It's about failing until you understand.
</div>

<br>

## Get to the Point, **What's the Underlying Theme?**

<html>
<head>
<style>
.card {
  background-color: #fdfdfd;
  border: 2px solid #ddd;
  border-radius: 12px;
  padding: 30px;
  text-align: center;
  margin: 40px auto;
  width: 80%;
  box-shadow: 2px 2px 12px rgba(0,0,0,0.1);
  font-size: 28px;
  font-weight: bold;
}

.highlight {
  display: inline-block;
  border-bottom: 4px solid orange;
  padding-bottom: 4px;
  margin: 0 4px;
}
</style>
</head>
<body>

<div class="card">
  <span class="highlight">Learning</span>. It's about <span class="highlight">failing</span> until you <span class="highlight">understand</span>.
</div>

</body>
</html>

<html>
<head>
<style>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 40px 0;
  gap: 30px;
}

.word-box {
  text-align: center;
}

.word {
  display: inline-block;
  padding: 20px 30px;
  border: 2px solid #ddd;
  border-radius: 10px;
  font-size: 28px;
  color: #FF8C00;
  font-weight: bold;
  margin-bottom: 10px;
  background-color: #fdfdfd;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

.symbol-box {
  display: inline-block;
  width: 30px;
  height: 30px;
  border: 2px solid #333;
  border-radius: 5px;
  text-align: center;
  line-height: 28px;
  font-weight: bold;
  font-size: 16px;
}
</style>
</head>
<body>

<div class="container">
  <div class="word-box">
    <div class="word">Learning</div><br>
    <div class="symbol-box">N</div>
  </div>
  <div class="word-box">
    <div class="word">Failing</div><br>
    <div class="symbol-box">-</div>
  </div>
  <div class="word-box">
    <div class="word">Understand</div><br>
    <div class="symbol-box">+</div>
  </div>
</div>

</body>
</html>

<html>
<head>
<style>
body {
  font-family: sans-serif;
  background-color: #fff;
  margin: 40px;
}

.container {
  display: flex;
  justify-content: center;
  gap: 100px;
  flex-wrap: wrap;
}

.oval-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
}

.top-symbol {
  margin-bottom: 20px;
  width: 45px;
  height: 45px;
  border: 2px solid #000;
  border-radius: 8px;
  font-size: 22px;
  font-weight: bold;
  text-align: center;
  line-height: 42px;
}

.oval {
  width: 340px;
  min-height: 140px;
  border: 2px solid #aaa;
  border-radius: 100px / 50px;
  background-color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 20px;
  font-size: 22px;
  font-weight: bold;
  position: relative;
}

.word-symbol-row {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin-top: 15px;
}

.word-box {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-width: 80px;
}

.symbol-box {
  width: 45px;
  height: 45px;
  border: 2px solid #000;
  border-radius: 8px;
  font-size: 22px;
  font-weight: bold;
  text-align: center;
  line-height: 42px;
  margin-top: 6px;
}
</style>
</head>
<body>

<div class="container">

  <!-- Phrase 1 -->
  <div class="oval-wrapper">
    <div class="top-symbol">+</div>
    <div class="oval">Learning to Fail</div>
    <div class="word-symbol-row">
      <div class="word-box">
        <span>Learning</span>
        <div class="symbol-box">N</div>
      </div>
      <div class="word-box">
        <span>Fail</span>
        <div class="symbol-box">-</div>
      </div>
    </div>
  </div>

  <!-- Phrase 2 -->
  <div class="oval-wrapper">
    <div class="top-symbol">N</div>
    <div class="oval">Understanding Learning</div>
    <div class="word-symbol-row">
      <div class="word-box">
        <span>Understanding</span>
        <div class="symbol-box">+</div>
      </div>
      <div class="word-box">
        <span>Learning</span>
        <div class="symbol-box">N</div>
      </div>
    </div>
  </div>

</div>

</body>
</html>





