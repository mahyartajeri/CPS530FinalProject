# CPS530FinalProject
# Page 1 Code:

<!DOCTYPE html>
<html>
<head>
<title>Page 1</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zen+Kurenaido&display=swap" rel="stylesheet">
<style>
    img {
        max-height: 400px;
        max-width: 400px; 
    }
</style>
</head>

<body style="font-family: Zen Kurenaido; background-color: aliceblue; text-align: center">
<h1>Semantic UI and Ruby on Rails</h1>
<div>
<h2>Semantic UI</h2>
<img src="https://react.semantic-ui.com/logo.png" alt="Semantic UI">
<h3>About</h3>
<p>Semantic UI is a development framework used for creating simple and attractive web applications. 
    It is often seen as a minimalist alternative to bootstrap making it a less well known, yet still effective framework. 
    It is not a very popular framework in general with only 1400 followers on GitHub. 
    It has a robust, well documented grid system which is very similar to Bootstrap. 
    Its simplicity and aesthetics make it very easy to learn and as such makes it a good option for beginners looking to create web applications. 
    This simplicity comes at a cost however as Semantic UI does lack the amenities of a framework such as Bootstrap. 
    It has less browser compatibility, a less reponsive design which can be an issue when developing mobile applications, 
    and a much smaller community making it more difficult to share and acquire knowledge about the framework. 
    Web Developers looking to create simple websites focusing primarily on aesthetic would enjoy using Semantic UI. 
    Anything more complicated however and they would be better off using a more thorough framework such as Angular.</p>
</div>
<div>
<h2>Ruby on Rails</h2>
<img src="https://avatars.githubusercontent.com/u/4223" alt="RoR">
<h3>About</h3>
<p>Ruby on Rails is an open source web development application written in the Ruby programming language. 
    It is very popular, with many well known applications such as GitHub, Shopify, and Twitch being made using Ruby on Rails. 
    This can be attributed to its reputation as a simple and effective tool, as well as its ease of access due to it being free. 
    Ruby on Rails is a backend web development framework and is a very simple languge to learn with much of its syntax being English
    keywords. Some more features are good documentation, good compatability with front-end frameworks, and a high development speed.
    Some downsides to using Ruby are a slow runtime speed, and a lack of flexibility when dealing with the development of apps with 
    very specific functionalities. For regular web applications however, Ruby on Rails is considered a perfect solution.</p>
</div>
</body>
</html>


#Page 2 Code:

<!DOCTYPE html>
<html>
<head>
<title>Page 2</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zen+Kurenaido&display=swap" rel="stylesheet">
</head>
<body style="font-family: Zen Kurenaido; background-color: aliceblue;">
<h1 style="text-align: center;">How to install Semantic UI and Ruby on Rails on Windows</h1>
<div>
    <h2>Semantic UI</h2>
    <h3>Step 1: Download the NodeJS Executable</h3>
    <p>Link to the download can be found on https://nodejs.org/en/</p>
    <h3>Step 2: Install Gulp</h3>
    <p>Enter into the command line: "npm install gulp-cli -g" <br> Next enter: "npm install gulp@4.0.0 -D"</p>
    <h3>Step 3: Make a project folder in the directory of your choice. Ex: C:\Desktop\my_folder</h3>
    <p>Don't forget to navigate to said folder using: cd C:\Desktop\my_folder</p>
    <h3>Step 4: Create your package.json file</h3>
    <p>Run: "npm init" in your project directory and press enter until prompted for yes</p>
    <h3>Step 5: Install Fomantic UI - A community ran fork of Semantic UI</h3>
    <p>Run: "npm install --ignore-scripts fomantic-ui"<br>
    Next run: "cd node_modules/fomantic-ui" <br> Next run: "npx gulp install" <br>
    You will then be prompted by Fomantic UI to choose your method of installation, Automatic is the easiest <br>
    Finally run: "npx gulp build"</p>
    <h3>You can now use the Semantic UI framwork<h3>
    <p>Make sure to include the following code in the header section of your html file: <br>
      	<code>
		    &lt;!-- You MUST include jQuery before Fomantic --&gt;
            &lt;script src="https://cdn.jsdelivr.net/npm/jquery@3.3.1/dist/jquery.min.js"&gt;&lt;/script&gt;
            &lt;link rel="stylesheet" type="text/css" href="/dist/semantic.min.css"&gt;
            &lt;script src="/dist/semantic.min.js"&gt;&lt;/script&gt;	
	    </code>
    </p>
    <h3>Alternatively, you can forgo the above steps and use a CDN provider</h3>
    <p>
        Simply include the following code in the header section of your html file: <br>
        <code>
            &lt;!-- You MUST include jQuery before Fomantic --&gt;
            &lt;script src="https://cdn.jsdelivr.net/npm/jquery@3.3.1/dist/jquery.min.js"&gt;&lt;/script&gt;
            &lt;link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/fomantic-ui@2.8.8/dist/semantic.min.css"&gt;
            &lt;script src="https://cdn.jsdelivr.net/npm/fomantic-ui@2.8.8/dist/semantic.min.js"&gt;&lt;/script&gt;
        </code>
    </p>
    
</div>

<div>
    <h2>Ruby on Rails</h2>
    <h3>Step 1: Install Ruby</h3>
    <p>Download an installation package from http://rubyinstaller.org/ <br>
    Make sure ruby is added to your path</p>
    <h3>Step 2: Install Rails</h3>
    <p>If you correctly installed Ruby, you should be able to run this command to install Rails: "gem install rails"</p>
    <h3>Step 3: Using NodeJS and and npm package manager, install Yarn</h3>
    <p>Run: "npm install --global yarn"</p>
    <h3>Step 4: Installation Verification</h3>
    <p>Run: "rails new demo" <br>
       Run: "cd demo" <br>
       Run: "rails server" <br>
       Now open your browse and type http://localhost:3000 <br>
       A ruby introduction site will appear meaning you are ready to start developing!</p>
</div>
</body>
</html>
