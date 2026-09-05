# CS-465-Full-Stack-Development-
<!DOCTYPE html>
<!-- Website template by freewebsitetemplates.com -->
<html>
<head>
	<meta charset="UTF-8">
	<title>About - Travlr Getaways Web Template</title>
	<link rel="stylesheet" href="css/style.css" type="text/css">
</head>
<body>
	<div id="background">
		<div id="page">
			<div id="header">
				<div id="logo">
					<a href="index.html"><img src="images/logo.png" alt="LOGO" height="100" width="200"></a>
				</div>
				<div id="navigation">
					<ul>
						<li>
							<a href="index.html">Home</a>
						</li>
						<li>
							<a href="travel.html">Travel</a>
						</li>
						<li>
							<a href="rooms.html">Rooms</a>
						</li>
						<li>
							<a href="meals.html">Meals</a>
						</li>
						<li>
							<a href="news.html">News</a>
						</li>
						<li class="selected">
							<a href="about.html">About</a>
						</li>
						<li>
							<a href="contact.html">Contact</a>
						</li>
					</ul>
				</div>
			</div>
			<div id="contents">
				<div class="box">
					<div>
						<div class="body">
							<h1>About</h1>
							<h2>We Have Free Templates for Everyone</h2>
							<p>
								Our website templates are created with inspiration, checked for quality and originality and meticulously sliced and coded. What's more, they're absolutely free! You can do a lot with them. You can modify them. You can use them to design websites for clients, so long as you agree with the <a href="http://www.freewebsitetemplates.com/about/terms/">Terms of Use</a>. You can even remove all our links if you want to.
							</p>
							<p>
								We Have More Templates for You. Looking for more templates? Just browse through all our <a href="http://www.freewebsitetemplates.com/">Free Website Templates</a> and find what you're looking for. But if you don't find any website template you can use, you can try our <a href="http://www.freewebsitetemplates.com/freewebdesign/">Free Web Design</a> service and tell us all about it. Maybe you're looking for something different, something special. And we love the challenge of doing something different and something special.
							</p>
							<hr>
							<div class="ads">
								<h2>Our Crews</h2>
								<p>
									Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc a arcu ipsum.
								</p>
								<h2>Amenities</h2>
								<p>
									Phasellus porta ultrices lorem vel luctus.Cras sodales nulla vitae eros fermentum consequat. Aenean at purus odio.
								</p>
							</div>
							<h2>Be Part of Our Community</h2>
							<p>
								If you're experiencing issues and concerns about this website template, join the discussion <a href="http://www.freewebsitetemplates.com/forums/">on our forum</a> and meet other people in the community who share the same interests with you.
							</p>
							<h2>Template details</h2>
							<p>
								Design version 14. Code version 4. Website Template details, discussion and updates for this <a href="http://www.freewebsitetemplates.com/discuss/beachresort/">Travlr Getaways Web Template</a>. Website Template design by <a href="http://www.freewebsitetemplates.com/">Free Website Templates</a>. Please feel free to remove some or all the text and links of this page and replace it with your own About content.
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div id="footer">
			<div>
				<ul class="navigation">
					<li>
						<a href="index.html">Home</a>
					</li>
					<li>
						<a href="travel.html">Travel</a>
					</li>
					<li>
						<a href="rooms.html">Rooms</a>
					</li>
					<li>
						<a href="meals.html">Meals</a>
					</li>
					<li>
						<a href="news.html">News</a>
					</li>
					<li class="active">
						<a href="about.html">About</a>
					</li>
					<li>
						<a href="contact.html">Contact</a>
					</li>
				</ul>
				<div id="connect">
					<a href="http://pinterest.com/fwtemplates/" target="_blank" class="pinterest"></a> <a href="http://freewebsitetemplates.com/go/facebook/" target="_blank" class="facebook"></a> <a href="http://freewebsitetemplates.com/go/twitter/" target="_blank" class="twitter"></a> <a href="http://freewebsitetemplates.com/go/googleplus/" target="_blank" class="googleplus"></a>
				</div>
			</div>
			<p>
				© 2023 by Travlr Getaways. All Rights Reserved
			</p>
		</div>
	</div>
</body>
</html>
Get-ExecutionPolicy -List 
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser 
Get-ExecutionPolicy -List 
Windoes PowerShell
Copyrite (c) 2023 by Travlr Getaways. All Rights Reserved.

Install the latest version of PowerShell for new features and improvements! https://aka.ms/PSwindows

PS C:\Windows\system32> Get-ExecutionPolicy -List
		Scope ExecutionPolicy
		----- ---------------
		MachinePolicy       Undefined
		UserPolicy          Undefined
		Process             Undefined
		CurrentUser         Undefined
		localMachine        Undefined

PS C:\Windows\system32> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

Execution Policy Change
The execution policy helps protect you from scripts that you do not trust. Changing the execution policy might expose you to the security risks described in the about_Execution_Policies help topic at https:/go.microsoft.com/fwlink/?LinkID=135170. Do you want to change the execution policy?
[Y] Yes  [A] Yes to All  [N] No  [L] No to All  [S] Suspend  [?] Help (default is "N"): Y
PS C:\Windoes\system32> Get-ExecutionPolicy -List
		Scope ExecutionPolicy
		----- ---------------
		MachinePolicy       Undefined
		UserPolicy          Undefined
		Process             Undefined
		CurrentUser         RemoteSigned
		localMachine        Undefined

PS C:\Windows\system32>
Get-ExecutionPolicy -List 
cd ~/travlr
npm install -g express-generator

PS C:\users\jayme\travlr> npm install -g express-generator
C:\Users\jayme\AppData\Roaming\npm\express -> C:\Users\jayme\AppData\Roaming\npm\node_modules\express-generator\bin\express
+ express-generator@4.16.1
added 10 packages in 2.123s
npm notice
npm notice New minor version of npm available! 9.6.7 -> 9.8.1
npm notice Changelog: https://github.com/npm/cli/releases/tag/v9.8.1
npm notice Run npm install -g npm@9.8.1 to update!
npm notice 
PS C:\users\jayme\travlr>
express --view=hbs --git --force 

PS C:\user\jayme> cd ~/travlr
PS C:\users\jayme\travlr> express --view=hbs --git --force
   create : travlr/
   create : travlr/package.json
   create : travlr/app.js
   create : travlr/public/
   create : travlr/public/javascripts/
   create : travlr/public/images/
   create : travlr/public/stylesheets/
   create : travlr/public/stylesheets/style.css
   create : travlr/routes/
   create : travlr/routes/index.js
   create : travlr/routes/users.js
   create : travlr/views/
   create : travlr/views/index.hbs
   create : travlr/views/layout.hbs
   create : travlr/views/error.hbs
   create : travlr/bin/
   create : travlr/bin/www
   create : travlr/.gitignore
   create : views/error.hbs
   create : views/index.hbs
   create : views/layout.hbs
   create : routes/index.js
   create : routes/users.js
   create : public/javascripts/
   create : public/images/
   create : public/stylesheets/
   create : public/stylesheets/style.css
   create : bin/www
   create : package.json
   create : .gitignore
   create : app.js
   create : package-lock.json
   create : travlr/.gitignore
   create : travlr/package.json
   create : travlr/app.js
   create : travlr/public/
   create : travlr/public/javascripts/
   create : travlr/public/images/
   create : travlr/public/stylesheets/
   create : travlr/public/stylesheets/style.css
   create : travlr/routes/
   create : travlr/routes/index.js
   create : travlr/routes/users.js
   create : travlr/views/
   create : travlr/views/index.hbs
   create : travlr/views/layout.hbs
   create : travlr/views/error.hbs
   create : travlr/bin/
   create : travlr/bin/www

   install dependencies:
	 > npm install	
	    run the app:
	 > DEBUG=travlr:* npm start

	 PS C:\users\jayme\travlr> 

	 npm install
	 PC C:\users\jayme\travlr> npm install


	 added 63 packages, and audited 64 packages in 5s

	 7 vulnerabilities (3 moderate, 4 critical)

	 To address all issues (including breaking changes), run:
	 npm audit fix --force

	 Run `npm audit` for details.
	 PC C:\users\jayme\travlr> 

	 npm audit 
	 PS C:\users\jayme\travlr> npm audit

	                       === npm audit security report ===
	Handlebars  <4.7.6
	Severity: critical
	Prototype Pollution in handlebars - https://npmjs.com/advisories/1383
    Arbitrary Code Execution in handlebars - https://npmjs.com/advisories/1315
	Prototype Pollution in handlebars - https://npmjs.com/advisories/1316
	Prototype Pollution in handlebars - https://npmjs.com/advisories/1317
	Arbitrary Code Execution in handlebars - https://npmjs.com/advisories/1318
	Denial of Service in handlebars - https://npmjs.com/advisories/1319
	Remote Code Execution in handlebars - https://npmjs.com/advisories/1320
	Prototype Pollution in handlebars - https://npmjs.com/advisories/1321
	Aribtrary Code Execution in handlebars - https://npmjs.com/advisories/1322
	Depends on vulnerable versions of optimist
	Fix available via `npm audit fix --force`.
	Will install hbs@4.2.0, which is outside the semver range of the current dependency.
	node_modules/express-handlebars
	  hbs  >=4.0.0
	Package: handlebars
	Patched in: >=4.7.7	
	node_modules/hbs

	minimist  <=0.2.3
	Serverity: Critical
	Arbitrary Code Execution in minimist - https://npmjs.com/advisories/117
	Depends on vulnerable versions of
	Prototype Pollution in minimist - https://gethub.com/advisories/GHSA-2h8g-5rj9-7v3m
Prototype Pollution in minimist - https://npmjs.com/advisories/GHSA-2h8g-5rj9-7v3m
Fix available via `npm audit fix --force`.
Will install hbs@4.2.0, which is outside the semver range of the current dependency.
node_modules/express-handlebars
  hbs  >=4.0.0
	 optimist  <=0.6.1

qs 6.5.2
Severity: Moderate
Denial of Service in qs - https://npmjs.com/advisories/28
servity: high

qs vulnerable to Regular Expression Denial of Service (ReDoS) - https://github.com/advisories/GHSA-7rjr-3j6c-5q5m
Fix available via `npm audit fix --force`.
Will install hbs@4.2.0, which is outside the semver range of the current dependency.
node_modules/express-handlebars
  hbs  >=4.0.0
  boidy-parser  >=1.0.0
  Depsends on vulnerable versions of qs
  node_modules/body-parser
	qs  >=6.0.0
	express  >=4.0.0-4.16.4 || 5.0.0-alpha.8
	Depends on vulnerable versions of body-parser
	Depends on vulnerable versions of qs

7 vulnerabilities (3 moderate, 4 critical)

To address all issues (including breaking changes), run:
  npm audit fix --force
PC C:\users\jayme\travlr> npm audit fix --force
npm WARN using --force Recommended protections disabled.
npm WARN audit Updating hbs to 4.2.0, which is a breaking change
npm WARN audit Updating minimist to 1.2.7, which is a breaking change
npm WARN audit Updating qs to 6.10.3, which is a breaking change

added 41 package, removed 1 packages, updated 3 packages, and audited 104 packages in 4s

12 packages are looking for funding
  run `npm fund` for details

  found 0 vulnerabilities
  PC C:\users\jayme\travlr> 

  PS C:\users\jayme\travlr> set DEBUG=travlr:* & npm start

  >travlr@0.0.0 start
  > node ./bin/www

  Server is running at http://localhost:3000

  GEt / 200 2.168 ms - 139
  GET /stylesheets/style.css 200 1.123 ms - 113
  GET /favicon.ico 404 0.123 ms - 150

PS C:\users\jayme\travlr> npm start

> travlr@0.0.0 start
> node ./bin/www

GET / 200 2.168 ms - 139
GET /stylesheets/style.css 200 1.123 ms - 113
GET /favicon.ico 404 0.123 ms - 150
GET / images/logo.png 200 1.456 ms - 234
GET / images/sea-sound.jpg 200 1.789 ms - 345
GET / images/dive-site.jpg 200 1.234 ms - 456
GeT/ images/meal.jpg 200 1.567 ms - 567
GeT/ images/room.jpg 200 1.890 ms - 678
GET/ images/food.jpg 200 1.234 ms - 789
GET/ images/meal2.jpg 200 1.456 ms - 890
GET/ images/meal3.jpg 200 1.678 ms - 901
GET/ css/stlye .css 400 41.234 ms - 1067

PC C:\users\jayme\travlr> git status
On branch main module
Your branch is up to date with 'origin/main'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	package-lock.json
	package.json
	npm-debug.log
	npm-debug.log.1
	npm-debug.log.2
	npm-debug.log.3
	npm-debug.log.4
	npm-debug.log.5
	npm-debug.log.6
	Gitignore
	app.js
	bin/
	node_modules/
	public/
	routes/
	views/
nothing added to commit but untracked files present (use "git add" to track)
PC C:\users\jayme\travlr> git add .
Warning: LF will be replaced by CRLF in package-lock.json.
The file will have its original line endings in your working directory.
Warning: copy of gitignore has been modified in the index. The version in the index will be used.
Warning:copy of app.js has been modified in the index. The version in the index will be used.
Warning: copy of bin/www has been modified in the index. The version in the index will be used.
Warning: copy of package.json has been modified in the index. The version in the index will be used.
PC C:\users\jayme\travlr> git commit -m "Initial commit"
[main 1a2b3c4] Initial commit
 12 files changed, 123 insertions(+)
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 .gitignore
 create mode 100644 app.js
 create mode 100644 bin/www
 create mode 100644 public/javascripts/
 create mode 100644 public/images/
 create mode 100644 public/stylesheets/
 create mode 100644 routes/index.js
 create mode 100644 routes/users.js
 create mode 100644 views/index.hbs
 create mode 100644 views/layout.hbs
PC C:\users\jayme\travlr> git push origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 1.23 KiB | 1.23 MiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
To

PC:\Users\jayme\travlr> git status
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean
    new file:   package-lock.json
	new file:   package.json
	new file:   .gitignore
	new file:   app.js
	new file:   bin/www
	new file:   public/javascripts/
	new file:   public/images/
	new file:   public/stylesheets/
	new file:   routes/index.js
	new file:   routes/users.js
	new file:   views/index.hbs
	new file:   views/layout.hbs	

PC C:\users\jayme\travlr> git config --global user.name "Michael Sanchez"
PC C:\users\jayme\travlr> git config --global user.email "michael, sanchez5.@SHNU.edu"
PC C:\users\jayme\travlr> git commit -m "Baseline Express website with static content"
[main 1a2b3c4] Baseline Express website with static content
 12 files changed, 123 insertions(+)
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 .gitignore
 create mode 100644 app.js
 create mode 100644 bin/www
 create mode 100644 public/javascripts/
 create mode 100644 public/images/
 create mode 100644 public/stylesheets/
 create mode 100644 routes/index.js
 create mode 100644 routes/users.js
 create mode 100644 views/index.hbs
 create mode 100644 views/layout.hbs
 PC C:\users\jayme\travlr> git push origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 1.23 KiB | 1.23 MiB/s, done.
