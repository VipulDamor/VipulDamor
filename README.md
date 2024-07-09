# About Me


Hello there 👋

👋 Hey! I am Vipul Damor,

Android Developer with 7+ years of experience. and published more than 60+ apps in google playstore. My expertise includes Android, Flutter, Kotlin, Java, XML, Jetpack Compose, MVVM, Clean Architecture, and Dagger Hilt. I am passionate about creating robust and user-friendly mobile applications that deliver exceptional user experiences. Let's discuss more if you have any exciting opportunities for me!

## Personal Information

- **Name:** Vipul Damor
- **Tagline:** Passionate Android Developer
- **Email:** vipuldamor@gmail.com


## Skills

- **OS:** Android
- **Languages:** Kotlin, Java,Dart
- **Frameworks:** Jetpack Compose,Flutter, MVVM, Clean Architecture
- **Tools:** Git, CI/CD, Code Coverage

## Experience

### Android Developer & Flutter Developer
**Eryushion Techsol Pvt. Ltd.** | Aug 2018 - Present
    
    - Led full lifecycle development of native, hybrid Android, and Flutter
      applications using Java, Kotlin, and Jetpack Compose.
    - Managed client relationships, ensuring timely and on-budget project delivery.
    - Oversaw resource allocation and collaborated with cross-functional teams to
      optimize productivity and project outcomes.


### Android Developer
**Grubbrr inc** | Nov 2017 - jul 2018

● Led the full lifecycle development of Android native applications for hotel
management solutions, including KIOSK self-ordering, Order Management,
and KDS Kitchen Display Systems.
● Utilized expertise in Java, Git, and Wi-Fi data synchronization, collaborating
on local database management, API integration, shared preferences, and
payment gateway implementation.

### Android Developer
**Poojara Telecom Pvt. Ltd.** | Jul 2016 - Oct 2017

- Designed and developed Android native applications for employee
management, attendance systems, and product dealing solutions.
- Ensured timely project delivery while effectively managing operational
resources to optimize productivity and maintain high-quality standards.


### Android Developer
**The DynamicIT** | Jan 2016 - Apr 2016

● Explored advanced concepts in Android architecture.
● Developed foundational skills in native Android app development.


## Projects

### Rajkot Kitchenware
An Android app for selling Kitchenware products

### HOCL
An Android app for selling MobileProducts, and Employee Management


## Social Links

- **LinkedIn:** [www.linkedin.com/in/vipuldamor](https://www.linkedin.com/in/vipuldamor)
- **GitHub:** [github.com/VipulDamor](https://github.com/VipulDamor)
- **Twitter:** [twitter.com/damorvips](https://twitter.com/damorvips)
- **Stackoverflow** [https://stackoverflow.com/users/14285339/damor-vipul]
- **Portfolio** [https://vipuldamor.my.canva.site/]
- **goole playstore** [https://play.google.com/store/search?q=1993developers&c=apps]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Hey For Fun i have translate info in Kotlin Class. 


```kotlin
data class AboutMe(
    val name: String = "Vipul Damor",
    val about : String = "
        I am a skilled Android Developer with 6+ years of experience. My expertise includes Android, Flutter, Kotlin, Java, XML, Jetpack                                   Compose, MVVM, Clean Architecture, and Dagger Hilt. I am passionate about creating robust and user-friendly mobile applications that                              deliver exceptional user experiences. Let's discuss more if you have any exciting opportunities for me!"
    val tagline: String = "Passionate Android Developer",
    val email: String = "vipuldamor@gmail.com",
    val address: String = "Rajkot, India",
    val os: List<String> = listOf("Android"),
    val languages: List<String> = listOf("Kotlin", "Java","Dart"),
    val frameworks: List<String> = listOf("Jetpack Compose",Flutter,"MVVM", "Clean Architecture"),
    val tools: List<String> = listOf("Git", " CI/CD", "Code Coverage"),
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

