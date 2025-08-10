<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Web3 & Backend Developer</title>
<style>
  body {
    margin: 0;
    height: 100vh;
    background: url('your-gif.gif') no-repeat center center fixed;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    overflow: hidden;
  }

  .overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.4); /* optional dark overlay for better blending */
    top: 0;
    left: 0;
  }

  .coding-img {
    position: relative;
    max-width: 500px;
    width: 80%;
    z-index: 2;
    mix-blend-mode: lighten; /* makes image blend with bg */
    animation: float 4s ease-in-out infinite;
  }

  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0px); }
  }
</style>
</head>
<body>
  <div class="overlay"></div>
  <img src="coding-image.png" alt="Coding" class="coding-img">
</body>
</html>
