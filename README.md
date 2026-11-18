# 🔑 Password Generator

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

A tiny random password generator, written twice: once in **C** and once in **Java**. Both pick random printable ASCII characters (letters, digits and symbols) to build a password.

It's a small project, but it was a nice way to compare how the same idea looks in two languages. 🔄

---

## ✨ What each version does

| Version | File | Behavior |
| ------- | ---- | -------- |
| 🅲 C | `passwordGenerator.c` | Asks you for the length, then prints a password of that length |
| ☕ Java | `Main.java` | Prints a 10-character password straight away |

Both use characters from ASCII `33` (`!`) to `126` (`~`), so the output mixes upper/lower case letters, numbers and symbols.

## 🚀 Run it

**C**

```bash
gcc passwordGenerator.c -o passgen
./passgen
```

```text
Length of the Password: 12
k#9vR!q2@Lp~
```

**Java**

```bash
javac Main.java
java Main
```

> ⚠️ This is a learning project. It uses `rand()` and `Math.random()`, which are fine for practice but not cryptographically secure. For real passwords, use a password manager.

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
