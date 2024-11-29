<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link
    href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
    rel="stylesheet"
  />
  <title>Particle Effect</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: #69e6c8;
    }
    canvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1; 
      display: block;
    }
  </style>
</head>
<body class="relative">
 
  <canvas id="particleCanvas"></canvas>
  

  <div class="flex flex-col min-h-screen  ">
    <main class="">
      <div
        class="flex flex-col justify-center items-center py-8 px-6 mx-auto md:h-screen"
      >
        <a
          class="flex justify-center items-center mb-8 text-3xl font-semibold lg:mb-10 dark:text-white"
          href="/"
          ><div class="flex justify-between items-center max-w-6xl mx-auto">
            <div class="flex items-center">
              <img
                class="h-20 w-20 rounded-lg object-cover"
                alt="logo"
                src="/assets/Bncc_logo.png"
              />
              <div class="ml-5 border-l-4 border-gray-400 pl-3">
                <h2 class="text-gray-800 font-bold text-lg">
                  Bangladesh National Cadet Corps
                </h2>
                <h3 class="text-gray-800 text-sm">
                  Daffodil International University
                </h3>
              </div>
            </div>
          </div></a
        >
        <div
          class="justify-center items-center w-full bg-white rounded-lg shadow lg:flex md:mt-0 lg:max-w-md xl:p-0 dark:bg-gray-800"
        >
          <div class="p-6 w-full sm:p-8 lg:p-10">
            <h1
              class="mb-3 text-2xl text-center font-bold text-gray-900 lg:text-3xl dark:text-white"
            >
              Sign in to your account
            </h1>
            <form class="mt-8">
              <div class="mb-6">
                <label
                  for="email"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >Your email</label
                ><input
                  required=""
                  type="email"
                  name="email"
                  id="email"
                  placeholder="name@gmail.com"
                  class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  value=""
                />
              </div>
              <div class="mb-6">
                <label
                  for="password"
                  class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                  >Your password</label
                ><input
                  required=""
                  type="password"
                  name="password"
                  id="password"
                  placeholder=""
                  class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  value=""
                />
              </div>
              <div class="flex items-start mb-6">
                <div class="flex items-center h-5">
                  <input
                    id="remember"
                    aria-describedby="remember"
                    name="remember"
                    type="checkbox"
                    class="w-4 h-4 bg-gray-50 rounded border-gray-300 focus:ring-3 focus:ring-blue-300 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:bg-gray-700 dark:border-gray-600"
                  />
                </div>
                <div class="ml-3 text-sm">
                  <label
                    for="remember"
                    class="font-medium text-gray-900 dark:text-white"
                    >Remember me</label
                  >
                </div>
                <a
                  class="ml-auto text-sm text-blue-500  hover:underline"
                  href="/forgot-password/"
                  >Forgot Password?</a
                >
              </div>
              <button
                class="text-white font-medium rounded-lg text-base px-5 py-3 w-full sm:w-auto text-center mb-6 bg-green-400"
                type="submit"
              >
                <span class="flex justify-center items-center"
                  >Sign in to account</span
                >
              </button>
              <div
                class="text-sm font-medium text-gray-500 dark:text-gray-400"
              >
                Not registered?<a
                  class="ml-1 text-blue-400 hover:underline dark:text-blue-500"
                  href="/register/"
                  >Create an account.</a
                >
              </div>
            </form>
          </div>
        </div>
      </div>
    </main>
  </div>

  <script>
    const canvas = document.getElementById('particleCanvas');
    const ctx = canvas.getContext('2d');

    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;

    const particles = [];
    const maxParticles = 100;

    class Particle {
      constructor(x, y, size, speedX, speedY) {
        this.x = x;
        this.y = y;
        this.size = size;
        this.speedX = speedX;
        this.speedY = speedY;
      }

      draw() {
        ctx.beginPath();
        ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
        ctx.fillStyle = 'white';
        ctx.fill();
      }

      update() {
        this.x += this.speedX;
        this.y += this.speedY;

        if (this.x > canvas.width) this.x = 0;
        if (this.x < 0) this.x = canvas.width;
        if (this.y > canvas.height) this.y = 0;
        if (this.y < 0) this.y = canvas.height;
      }
    }

    for (let i = 0; i < maxParticles; i++) {
      const size = Math.random() * 3 + 1;
      const x = Math.random() * canvas.width;
      const y = Math.random() * canvas.height;
      const speedX = (Math.random() - 0.5) * 2;
      const speedY = (Math.random() - 0.5) * 2;

      particles.push(new Particle(x, y, size, speedX, speedY));
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);

      particles.forEach((particle) => {
        particle.update();
        particle.draw();
      });

      requestAnimationFrame(animate);
    }

    animate();

    window.addEventListener('resize', () => {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
    });
  </script>
</body>
</html>
