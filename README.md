# About Me

## Introduction

hey this is me passionate Android Developer 

## Personal Information

- **Name:** Vipul Damor
- **Tagline:** Passionate Android Developer
- **Email:** vipuldamor@gmail.com


## Skills

- **OS:** Android
- **Languages:** Kotlin, Java,Dart
- **Frameworks:** Jetpack Compose,Flutter, MVVM, Clean Architecture
- **Tools:** Git, Pipelines, Code Coverage

## Experience

### Android Developer & Flutter Developer
**Eryushion Techsol Pvt. Ltd.** | Aug 2018 - Present

Developed and maintained Android applications.Built cross-platform mobile apps using the Flutter framework.

### Android Developer
**Grubbrr inc** | Nov 2017 - jul 2018

Developed and maintained Android applications

### Android Developer
**Poojara Telecom Pvt. Ltd.** | Jul 2016 - Oct 2017

Developed and maintained Android applications


### Android Developer
**The DynamicIT** | Jan 2016 - Apr 2016

Android Trainee also Developed and maintained Android applications


## Projects

### Rajkot Kitchenware
An Android app for selling Kitchenware products

### HOCL
An Android app for selling MobileProducts, and Employee Management


## Social Links

- **LinkedIn:** [www.linkedin.com/in/vipuldamor](https://www.linkedin.com/in/vipuldamor)
- **GitHub:** [github.com/VipulDamor](https://github.com/VipulDamor)
- **Twitter:** [twitter.com/damorvips](https://twitter.com/damorvips)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Hey For Fun i have translate info in Kotlin Class. 


```kotlin
data class Resume(
    val name: String = "Vipul Damor",
    val tagline: String = "Passionate Android Developer",
    val email: String = "vipuldamor@gmail.com",
    val address: String = "Rajkot, India",
    val os: List<String> = listOf("Android"),
    val languages: List<String> = listOf("Kotlin", "Java","Dart"),
    val frameworks: List<String> = listOf("Jetpack Compose",Flutter,"MVVM", "Clean Architecture"),
    val tools: List<String> = listOf("Git", "Pipelines", "Code Coverage"),
    val experience: List<Experience> = listOf(
        Experience(
            title = "Android Developer And Flutter Developer",
            company = "Eryushion Techsol Pvt. Ltd.",
            duration = "Aug 2018 - Present",
            description = "Developed and maintained Android applications.Built cross-platform mobile apps using the Flutter framework."
        ),
        Experience(
            title = "Android Developer",
            company = "Grubbrr inc",
            duration = "Nov 2017 - jul 2018",
            description = "Developed and maintained Android applications"
        ),
         Experience(
            title = "Android Developer",
            company = "Poojara Telecom Pvt. Ltd.",
            duration = "Jul 2016 - Oct 2017",
            description = "Developed and maintained Android applications"
        ),
         Experience(
            title = "Android Developer",
            company = "The DynamicIT",
            duration = "Jan 2016 - Apr 2016",
            description = "Android Trainee also Developed and maintained Android applications"
        )
    ),
    val projects: List<Project> = listOf(
        Project(
            name = "Rajkot Kitchenware",
            description = "An Android app for selling Kitchenware products",
            url = ""
        ),
        Project(
            name = "HOCL",
            description = "An Android app for selling MobileProducts, and Employee Management",
            url = ""
        )
    ),
    val socialLinks: List<SocialLink> = listOf(
        SocialLink(
            platform = "LinkedIn",
            url = "https://www.linkedin.com/in/vipuldamor"
        ),
        SocialLink(
            platform = "GitHub",
            url = "https://github.com/VipulDamor"
        ),
        SocialLink(
            platform = "Twitter",
            url = "https://twitter.com/damorvips"
        )
    )
)

data class Experience(
    val title: String,
    val company: String,
    val duration: String,
    val description: String
)

data class Project(
    val name: String,
    val description: String,
    val url: String
)

data class SocialLink(
    val platform: String,
    val url: String
)

