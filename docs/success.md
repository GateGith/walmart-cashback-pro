---
title: "Success!"
layout: default
permalink: /success/
---

<div class="container">
  <div class="check">✓</div>
  <h1>Cashback Activated!</h1>
  
  <div class="steps">
    <div class="step done">Offer Complete</div>
    <div class="step">Processing</div>
    <div class="step">PayPal Deposit</div>
  </div>

  <p>Contact support with ID:<br>
  <span id="ref">WCB-${Date.now().toString().slice(-6)}</span></p>

  <footer>
    <a href="/verify">Back</a>
  </footer>
</div>

<style>
.check {
  font-size: 60px;
  color: #0071ce;
  text-align: center;
  margin: 20px 0;
}
.steps {
  display: flex;
  justify-content: space-between;
  margin: 30px 0;
}
.step {
  text-align: center;
  color: #666;
}
.done {
  color: #0071ce;
  font-weight: bold;
}
#ref {
  color: #0071ce;
  font-size: 1.2em;
}
</style>
