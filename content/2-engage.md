---
title: Be Engaging
nav: Engage
---

<!-- Fade-in animation CSS -->
<style>
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translate3d(0, 40px, 0);
  }
  to {
    opacity: 1;
    transform: none;
  }
}

.fade-in-up {
  animation: fadeInUp 1s ease forwards;
  opacity: 0;
  animation-delay: 0.3s;
  animation-fill-mode: forwards;
}
</style>

<div class="card mb-4 fade-in-up">
  <div class="card-body text-center">
    <blockquote class="blockquote">
      <p class="fs-4 fw-bold">
        "Good design is making something intelligible and memorable. Great design is making something memorable and meaningful."
      </p>
      <footer class="blockquote-footer mt-2">Dieter Rams</footer>
    </blockquote>
  </div>
</div>

# Engage with the Audience

<div class="row">
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-secondary">
      <div class="card-body text-center">
        <p class="fw-bold">It takes a village</p>
        <p>Make the audience feel like they were involved.</p>
      </div>
    </div>
  </div>
  
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-secondary">
      <div class="card-body text-center">
        <p class="fw-bold">Silence is just an effect</p>
        <p>The first one to talk, buys.</p>
      </div>
    </div>
  </div>
  
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-secondary">
      <div class="card-body text-center">
        <p class="fw-bold">Live performances should be alive</p>
        <p>You should be able to go off script and/or abandon visual aids.</p>
      </div>
    </div>
  </div>
</div>

<br>

# Let the Audience Engage with the Content

<div class="row">
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-primary">
      <div class="card-body text-center">
        <p class="fw-bold">Ditch the jargon</p>
        <p>You have to translate before you can communicate.</p>
      </div>
    </div>
  </div>
  
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-primary">
      <div class="card-body text-center">
        <p class="fw-bold">Let go of the rigor</p>
        <p>Everyone assumes you're the expert. You don't need to prove yourself — you need to be heard.</p>
      </div>
    </div>
  </div>
  
  <div class="col-md-4 mb-4 fade-in-up">
    <div class="card h-100 border-primary">
      <div class="card-body text-center">
        <p class="fw-bold">Turn the listeners into collaborators</p>
        <p>The audience should have questions <strong>and comments</strong> they didn't arrive with.</p>
      </div>
    </div>
  </div>
</div>

<br>

# Make Them Care

<div class="text-center mb-4">
  <button type="button" class="btn btn-warning btn-lg" data-bs-toggle="modal" data-bs-target="#finalModal">
    Final Message
  </button>
</div>

<!-- Final Modal -->
<div class="modal fade" id="finalModal" tabindex="-1" aria-labelledby="finalModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg modal-dialog-centered">
    <div class="modal-content" style="height: 75vh;">
      <div class="modal-header">
        <h5 class="modal-title w-100 text-center fw-bold" id="finalModalLabel">The Point</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      
      <div class="modal-body d-flex flex-column justify-content-between">
        <div class="text-center" style="font-size: 2rem; margin-top: 20px;">
          <em>If there's no point to your presentation, then there's no point to remember it.</em>
        </div>
        
        <div class="text-center mt-4">
          <img src="statdept.jpg" alt="Image 1" style="max-width: 40%; margin: 10px;">
          <img src="statclub.jpg" alt="Image 2" style="max-width: 40%; margin: 10px;">
        </div>
        
        <div class="text-center mt-3" style="font-size: 0.9rem; color: #6c757d;">
          Thank you to K-State, the Department of Statistics, and the Stat Club for giving me this opportunity.<br>
          Special thanks to the ASA and Savills for their contributions to this year's celebration of data!
        </div>
      </div>
    </div>
  </div>
</div>
