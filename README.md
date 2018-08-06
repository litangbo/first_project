# first_project

# 1 HTTPS的方式
	https://github.com/litangbo/first_project.git

	// …or create a new repository on the command line
	echo "# Android_Study" >> README.md
	git init
	git add README.md
	git add .
	git commit -m "first commit"
	git remote add origin https://github.com/litangbo/first_project.git
	git push -u origin master

	// …or push an existing repository from the command line
	git remote add origin https://github.com/litangbo/first_project.git
	git push -u origin master

# 2 SSH的方式
	git@github.com:litangbo/Android_Study.git

	// …or create a new repository on the command line
	echo "# Android_Study" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin git@github.com:litangbo/first_project.git
	git push -u origin master

	// …or push an existing repository from the command line
	git remote add origin git@github.com:litangbo/first_project.git
	git push -u origin master

# 3 后续提交
	git add .
	git commit -m "mark"
	git push -u origin master
