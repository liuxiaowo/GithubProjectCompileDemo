# GithubProjectCompileDemo
#ʹ�÷�ʽ��
	gradle���ͣ�
	����һ��������ӵ��洢��ĩβ�ĸ�build.gradle�У�
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	����������������ϵ:
	dependencies {
		compile 'com.github.User:Repo:Tag'
	}