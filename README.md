# GithubProjectCompileDemo
#使用方式：
	gradle类型：
	步骤一：将其添加到存储库末尾的根build.gradle中：
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	步骤二：添加依赖关系:
	dependencies {
		compile 'com.github.User:Repo:Tag'
	}