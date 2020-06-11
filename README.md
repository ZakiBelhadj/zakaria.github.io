# zakaria.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <title>Zakaria Belhadj</title>
</head>
<body onload="typeWriter()">
  <div class="container py-16">
    <h1 class="text-black font-semibold text-6xl my-4" id="hello"></h1>
    <h2 class="text-black font-mono font-bold text-3xl  mt-10">My name is Zakaria Belhadj.</h2>
    <div class="flex justify-start items-center ">
        <img class="w-8 h-8 rounded-full -mt-1" src="https://avatars0.githubusercontent.com/u/6919003?s=460&u=5bfca584fd8de75292f4230456e8d9ba2f66e86a&v=4" >
        <h4 class="text-black font-mono text-sm ml-2 mt-2">@ZakiBelhadj</h4>
    </div>
      <div class="max-w-3xl">
        <p class="font-serif font-medium font-mono antialiased text-xl mt-6 leading-relaxed">
            I'm a full stack web developer with the skills & knowledge necessary to create user-friendly, interactive, & fun web applications.
         </p>
        <p class="font-serif font-medium font-mono antialiased text-xl mt-6 leading-relaxed">
            I am an independent software developer. Most of my work is open source and publicly available on <a target="_blank" href="https://github.com/ZakiBelhadj" class="p-2 bg-black rounded-lg text-white">GitHub</a>.
        <p class="font-serif font-medium font-mono text-xl mt-6 leading-relaxed">
        I've worked extensively with web technologies including <a href="https://nodejs.org/en/" target="_blank" class="p-2 bg-green-500 rounded-lg text-white">NodeJS</a>, <a href="https://reactjs.org/" target="_blank" class="p-2 bg-blue-400 rounded-lg text-white">ReactJs</a>, <a href="https://vuejs.org/" target="_blank" class="p-2 bg-teal-400 rounded-lg text-white">VueJs</a> and <a href="https://laravel.com/" target="_blank" class="p-2 bg-red-400 rounded-lg text-white">Laravel</a> to create reliable, scalable, and maintainable software.
        </p>
        <p class="font-serif font-medium font-mono antialiased text-xl mt-6 leading-relaxed">
            Outside of programming, I enjoy video games, Tv series and playing football with my friends.
        </p>
        <p class="font-serif  font-medium font-mono antialiased text-xl mt-6 leading-relaxed">
            Follow me : <a href="https://www.linkedin.com/in/zakaria-belhadj-739607102/" target="_blank" class="p-2 bg-blue-600 rounded-lg text-white">Linkedin</a>
            <a href="https://medium.com/@zakibel" target="_blank" class="p-2 rounded-lg text-white bg-gray-800">Medium</a>
            <a href="https://dev.to/zakaria_belhadj" target="_blank" class="p-2 bg-black rounded-lg text-white ">DEV</a>
        </p>
    </div>
  </div>
    <!-- Load the script on the page. -->
    <script>
        var i = 0;
        var txt = 'Hello Everyone.'; 
        var speed = 70;     
         function typeWriter() {
          if (i < txt.length) {
          document.getElementById("hello").innerHTML += txt.charAt(i);
          i++;
          setTimeout(typeWriter, speed);
         }
       }
      </script>
</body>
</html>
