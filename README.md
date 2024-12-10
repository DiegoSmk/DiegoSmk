# 👋 Olá! Bem-vindo ao meu GitHub!

```kotlin
import classes.*

fun Human.haveCoffee() {
    println("$name is having coffee... ☕🔥 Ready to dive into code!")
}

fun Human.celebrateSuccess(project: String) {
    println("$name just finished the project '$project'! 🎉🎉 Time to take a break with some coffee... ☕")
}

fun main() {
    val diegoSmk = Human(
        name = "Diego Pena",
        company = "Brazilian Navy", // 🎖️ Militar
        role = "Second Sergeant",
        specialization = "Communications Technician",

        skills = Skills(
            languages = listOf("Kotlin", "JavaScript", "TypeScript", "Python"), // 💻 Linguagens
            focus = listOf("Kotlin", "Jetpack Compose", "KMP") // 🔧 Tecnologias em foco
        ),

        interests = Interests(
            cryptography = true, // 🔐 Criptografia
            ai = true, // 🤖 Inteligência Artificial
        ),

        education = Education(
            course = "Software Engineering", // 📚 Engenharia de Software
            status = EducationStatus.CURRENTLY_ENROLLED // 🎓 Em andamento
        ),

        links = Links(
            linkedin = "www.linkedin.com/in/diego-pena-2b1967334",
        )
    )

    diegoSmk.haveCoffee()
}
```
