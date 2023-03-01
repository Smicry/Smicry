<div class="ferris">
<img height="150" src="https://user-images.githubusercontent.com/11643477/154806909-b00a9c79-bdb7-4086-a134-d6a29bca228e.png">
</div>

<style>
.ferris {
  animation: 4s linear 0s infinite alternate rise, 4s linear 0s infinite
      alternate bounce;
}

@keyframes rise {
  from {
    transform: translateY(110vh);
  }
  to {
    transform: translateY(0);
  }
}

@keyframes bounce {
  from {
    transform: translateX(-50vw);
  }
  to {
    transform: translateX(50vw);
  }
}
</style>
