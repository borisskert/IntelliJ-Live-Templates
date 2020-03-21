# My IDEA IntelliJ Live-Templates

## Installation

Copy the files (or git clone this repo) to directory `<configuration_directory>/templates`.

The value `<configuration_directory>` depends on the IntelliJ-version and operating system. See [IntelliJ documentation](https://www.jetbrains.com/help/idea/tuning-the-ide.html#config-directory) for further information.

For example on Linux and IntelliJ 2019.3 you can find your configuration at `~/.IntelliJIdea2019.3/config`.
In a MacOS environment you will find your configuration at `~/Library/Preferences/IdeaIC2019.3/templates`.

To keep this configuration up-to-date you can clone this git-repo into the configuration directory.

## Templates

### Java

#### General

| name       | Description |
|------------|-------------|
| `req`      | Generates a statement to verify if a parameter is not null with `java.util.Objects.requireNonNull` |

#### Junit 4

| name       | Description |
|------------|-------------|
| `test4`    | Generates a JUnit 4 `@Test` method block |
| `bef4`     | Generates a JUnit 4 `@Before` method block |

#### Junit 5

| name       | Description |
|------------|-------------|
| `test5`    | Generates a JUnit 5 `@Test` method block |
| `bef5`     | Generates a JUnit 5 `@Test` method block |
| `aexc5`    | Generates a JUnit 5 try-catch block which asserts the thrown Exception type and message |
| `ntest5`   | Generates a JUnit 5 nested test class |
| `athrows5` | Generates a JUnit 5 `assertThrows(....class, () -> ...)` statement |

#### Hamcrest

| name       | Description |
|------------|-------------|
| `aeq`      | Generates a Hamcrest `assertThat(..., is(equalTo(...))` statement |
| `ainstanceof` | Generates a Hamcrest `assertThat(..., is(instanceOf(...)));` statement |
| `anull`    | Generates a Hamcrest `assertThat(..., is(not(nullValue()))` statement |
| `aneq`     | Generates a Hamcrest `assertThat(..., is(not(equalTo(...)))` statement |
| `ansame`   | Generates a Hamcrest `assertThat(..., is(not(sameInstance(...))))` statement |
| `asame`    | Generates a Hamcrest `assertThat(..., is(sameInstance(...)))` statement |
