<template>
  <div>
    <h1>Face detection using the MediaPipe Face Detector task</h1>

    <section id="demos" class="invisible">
      <h2>Demo: Detecting Faces</h2>
      <p><b>Click on an image below</b> to detect faces in the image.</p>

      <div class="detectOnClick">
        <img
          src="https://assets.codepen.io/9177687/female-4572747_640.jpg"
          width="100%"
          crossorigin="anonymous"
          title="Click to get classification!"
        />
      </div>
      <div class="detectOnClick">
        <img
          src="https://assets.codepen.io/9177687/idea-gcbe74dc69_1920.jpg"
          width="100%"
          crossorigin="anonymous"
          title="Click to get classification!"
        />
      </div>

      <h2>Demo: Webcam continuous face detection</h2>
      <p>
        Detect faces from your webcam. When ready click "enable webcam" below
        and accept access to the webcam.
      </p>
      <div id="liveView" class="videoView">
        <button id="webcamButton" class="mdc-button mdc-button--raised">
          <span class="mdc-button__ripple"></span>
          <span class="mdc-button__label">ENABLE WEBCAM</span>
        </button>
        <video id="webcam" autoplay playsinline></video>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
</script>

<style>
</style>
