# CLI Greeting App

This repository includes **three implementations** of a CLI application that greets the user in multiple languages and displays the text in appropriate colors.

All versions, built with **Maven**, **Gradle**, or **NPM**, can be executed from the command line and accept an **optional language parameter**.

> If no language is specified, the default language is **English**.

---

## Running the Applications

### Maven / Gradle Versions

To run the Maven or Gradle application directly from the command line:

#### 1. Add the `bin` folder to your `PATH`

Temporary options:

```bash
export PATH=$PATH:$(pwd)/bin
```

or (for Gradle build output):

```bash
export PATH=$PATH:$(pwd)/build/install/hello-gradle/bin
```

#### 2. Run the application

```bash
hello-maven
```

or

```bash
hello-gradle
```

---

### NPM Version

#### 1. Install the package globally

```bash
npm install -g
```

#### 2. Run the application

```bash
hello-npm es
```

Replace `es` with any supported language code.

---

## Language Support

* Language parameter is optional
* Defaults to **English**
* Oher possible languages: **German, Spanish, Romanian**

Example:

```bash
hello-npm de
```

---

## Summary

* 3 implementations: Maven, Gradle, NPM
* CLI-based usage
* Optional language parameter
* Colored output per language
