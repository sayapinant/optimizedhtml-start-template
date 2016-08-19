<h1>OptimizedHTML - Start HTML Template</h1>

<p>OptimizedHTML is all-inclusive, optimized for Google PageSpeed Start HTML5 template with Bootstrap (grid only), Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Imagemin, Vinyl-FTP, Bower (libs path) and Bourbon support.</p>

<p>OptimizedHTML Start Template uses the best practices of web development and optimized for Google PageSpeed.</p>

<p>Cross-browser compatibility: IE9+.</p>

<p>The template uses a Sass with <strong>Sass</strong> syntax and project structure with source code in the directory <strong>app/</strong> and production folder <strong>dist/</strong>, that contains ready project with optimized HTML, CSS, JS and images.</p>

<h2>How to use OptimizedHTML</h2>

<ol>
	<li>Download <strong>optimizedhtml-start-template</strong> from GitHub;</li>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run template: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via FTP;</li>
	<li><strong>clearcache</strong>: clear all gulp cache;</li>
</ul>

<h2>Rules for working with the starting template</h2>

<ol>
	<li>All HTML files should have similar content to a file <strong>app/index.html</strong>;</li>
	<li><strong>Template Basic Images Start</strong> comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);</li>
	<li><strong>Load Fonts CSS Start</strong> comment in app/index.html: use <strong>loadCSS</strong> function, if the site is located in a subfolder. Use (uncomment) <strong>loadLocalStorageCSS</strong>, if the site is at the root. One of the lines should always be commented out. All fonts are connected in <strong>app/sass/fonts.sass</strong> with Bourbon;</li>
	<li><strong>Custom Browsers Color Start</strong> comment in app/index.html: set the color of the browser head on a variety of devices;</li>
	<li><strong>Custom HTML</strong> comment in app/index.html - all your custom HTML;</li>
	<li><strong>Optimized loading JS Start</strong> comment in app/index.html: loading all scripts;</li>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.sass</strong>;</li>
	<li>All Bootstrap media queries placed in <strong>app/sass/_media.sass</strong>;</li>
	<li>All jQuery libraries CSS styles placed in <strong>app/sass/_libs.sass</strong>;</li>
	<li>All basic styles (html, body, fonts, buttons, etc...) placed in <strong>app/sass/_base.sass</strong>;</li>
	<li>In the file <strong>app/header.sass</strong> should be placed all styless, responsible for displaying the first screen (on the biggest screens) on all pages;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching in web server.</li>
</ol>
