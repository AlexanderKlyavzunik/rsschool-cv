# [rsschool-cv](https://github.com/rolling-scopes-school)

## **Alexander Klyauzunik**

******

### **Contact information:**


E-mail: olegritov@mail.ru\
Telegram: @Olegsandrr\
[Github](https://github.com/AlexanderKlyavzunik)

******

### **Briefly about myself:**

 I've never seen myself as a web-developer, so my main language is C++, but I've also managed to develop a few skills in HTML/CSS \
 I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

 ***

 ### **Skills and Proficiency:**

* C++, QT
* HTML
* CSS

***
### **Code Example:**

*Following code is a timer realisation for C++, which outputs the amount of time beetween the object being constructed and destucted*
```
#pragma once
#include<chrono>
#include<iostream>
class Simple_Timer
{
public:

	Simple_Timer()
    {
	 start = std::chrono::high_resolution_clock::now();
    }

	~Simple_Timer()
    {
	 end = std::chrono::high_resolution_clock::now();
	 std::chrono::duration<float>duration = end - start;
	 std::cout << "completed in " << duration.count() << " seconds";
    }

private:
	std::chrono::time_point<std::chrono::steady_clock> start, end;
};
```

***

### **Languages:**

* Belarusian - Native
* Russian - Native
* English - Intermediate