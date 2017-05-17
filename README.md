# GithubProjectCompileDemo<br/>
#使用方式：<br/>
	gradle类型：<br/>
	步骤一：将其添加到存储库末尾的根build.gradle中：<br/>
	allprojects {<br/>
		repositories {<br/>
			...<br/>
			maven { url 'https://jitpack.io' }<br/>
		}<br/>
	}<br/>
	步骤二：添加依赖关系:<br/>
	dependencies {<br/>
		compile 'com.github.User:Repo:Tag'<br/>
	}<br/>