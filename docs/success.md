---
title: "Cashback Activated!"
layout: default
permalink: /success/
---

<div class="container">
  <div class="checkmark">✓</div>
  <h1>Your Cashback Is Processing!</h1>

  <div class="status">
    <div class="step completed">Offer Verified</div>
    <div class="step">Payment Processing</div>
    <div class="step">PayPal Transfer</div>
  </div>

  <div class="support">
    <p>Contact Support ID:<br>
    <span id="refID">WCB-${Date.now().toString().slice(-6)}</span></p>
  </div>

  <footer>
    <a href="/verify">← Back to Verification</a>
  </footer>
</div>

<style>
.checkmark {
  font-size: 4em;
  color: #0071ce;
  text-align: center;
  margin: 20px 0;
}

.status {
  display: flex;
  justify-content: space-between;
  margin: 30px 0;
}

.step {
  color: #666;
  text-align: center;
}

.completed {
  color: #0071ce;
  font-weight: bold;
}

#refID {
  color: #0071ce;
  font-size: 1.2em;
}
</style>

<script>
document.getElementById('refID').textContent = `WCB-${Date.now().toString().slice(-6)}`;
</script>
