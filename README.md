### Hi there 👋

data class Vipul(
    val name: String = "Vipul Damor",
    val tagline: String = "Passionate Android Developer",
    val email: String = "vipuldamor@gmail.com",
    val phoneNumber: String = "+91 8849615440",
    val address: String = "Rajkot, India",
    val os: List<String> = listOf("Android"),
    val languages: List<String> = listOf("Kotlin", "Java","Dart"),
    val frameworks: List<String> = listOf("Jetpack Compose", "MVVM", "Clean Architecture"),
    val tools: List<String> = listOf("Git", "Pipelines", "Code Coverage"),
    val experience: List<Experience> = listOf(
        Experience(
            title = "Senior Android Developer",
            company = "Awesome Tech Solutions",
            duration = "2018 - Present",
            description = "Developed and maintained Android applications."
        ),
        Experience(
            title = "Flutter Developer",
            company = "Fantastic Apps Studio",
            duration = "2016 - 2018",
            description = "Built cross-platform mobile apps using the Flutter framework."
        )
    ),
    val projects: List<Project> = listOf(
        Project(
            name = "Project A",
            description = "An Android app for task management.",
            url = "https://example.com/projectA"
        ),
        Project(
            name = "Project B",
            description = "A Flutter app for finance tracking.",
            url = "https://example.com/projectB"
        )
    ),
    val socialLinks: List<SocialLink> = listOf(
        SocialLink(
            platform = "LinkedIn",
            url = "https://www.linkedin.com/in/johndoe"
        ),
        SocialLink(
            platform = "GitHub",
            url = "https://github.com/johndoe"
        ),
        SocialLink(
            platform = "Twitter",
            url = "https://twitter.com/johndoe"
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


