# LeapFix

LeapFix is a powerful VSCode extension designed to perform SAST methodology or static security analysis on your code. It scans the lines of code in your files for vulnerabilities, providing descriptions and links on "how to fix the vulnerabilities" found. This allows developers to identify and fix vulnerabilities while coding. The extension identifies different types of vulnerabilities across various frameworks and programming languages.


### Plugin free

This plugin is completely free and does not require authentication, registration, create an account or generate credentials.


#### Supported language(s) and Frameworks(s)/Plataforms(s)

| **Player**                                                  | **Language**  |  **Framework(s)/Platforms(s)**    |      **File Extension(s)**      |
|:-----------------------------------------------------------:|:-------------:|:---------------------------------:|:-------------------------------|
|   <img src="https://i.imgur.com/tzDzglO.png" width="23">    |    Dart       |           Flutter                 |                   .dart         |
|   <img src="https://i.imgur.com/eEROTJO.png" width="23">    |    Golang     |           GoLang, Protobuf                  |                   .go           |  
|   <img src="https://i.imgur.com/CY6MjpZ.png" width="23">    | JavaScript    | Angular, NodeJS, React and VueJS                    |                   .js           |  
|   <img src="https://i.imgur.com/hVfAYjO.png" width="23">    | PHP           | CakePHP, CodeIgniter, Kohana, Laravel, Smarty, Symfony,bWapp, etc                  | .php,.php3,.php5.php6,.phtml,.pthm,.tpl,.ctp           | 
|   <img src="https://i.imgur.com/uoPxpbq.png" width="23">    | Python        |           DJango, FastAPI, Flask, PyQt, Tkinter,Kivy, etc                  |                   .py           | 
|   <img src="https://i.imgur.com/7b8hZlX.png" width="23">    | Perl          |  Dancer2,Mojolicious,Catalyst,Plack, Mason,Moose,Dist::Zilla etc                  |                   .pl,pm,psgi,plx           | 
|   <img src="https://i.imgur.com/bItTI1B.png" width="23">    | Ruby          |           Ruby on Rails                  |                   .rb           | 
|   <img src="https://i.imgur.com/R771Aj0.png" width="23">    | TypeScript    |           Angular, React and VueJS                  |                   .ts           | 
|   <img src="https://i.imgur.com/TXo8bMh.png" width="23">    | ADVPL    |           TOTVS Framework AdvPL                  |                   .prw           | 


## How to use

Run a new scan from your IDE even before committing your code or project.

To make the plugin scan and search for vulnerabilities in your code, press:

```sh
Ctrl+Shift+P
```

Select the command: 

```sh
Run SCAN
```
This command will scan the current file for vulnerabilities.

Se vulnerabilities are found, a tab will open pointing out the details of the vulnerabilities, along with a description and links on how to fix them.


## Result 

During code scans, vulnerabilities that appear will be highlighted in a tab:
![img-github](https://github.com/user-attachments/assets/394d6f08-584e-4739-9d61-080a789d4bd9)

Watch the video on how LeapFix works for different languages:
![leapfix](https://github.com/user-attachments/assets/f53ea628-dd83-4a61-9a7c-5407e18c33c8)

## Vulnerability remediation detail

When we scan the lines of code and vulnerabilities we find examples of how to fix the vulnerabilities.
For a better understanding of vulnerabilities, we offer an example of vulnerable code and an example of safe code to implement in your application.
I see examples of how developers will view the breakdown and example of vulnerable and secure code:

### 1 - [Remote Command Execution - GoLang](https://leapfix.co/?id=e5d9087fbff347f2d1cb8c5a55fc417d)

### 2 - [Insecure Deserialization - Ruby](https://leapfix.co/?id=f2b1e4a6c8d3a9e7b5c2d1f4e9a6b8d)

### 3 - [Potential SQL Injection in SELECT - PHP ](https://leapfix.co/?id=15c501fae8c2c7b72260534844f93d63)

### 4 - [XSS via Unsanitized Output - TypeScript (ReactJS)](https://leapfix.co/?id=ae2b1fca515949e5d54fb22b8ed95575)

### 5 - [TLS 1.0: Insufficient Cryptographic Algorithm Strength  - ADVPL](https://leapfix.co/?id=6adc689380264659017c2d6094e75b4e)

### 6 - [XML External Entities (XXE) - Python](https://leapfix.co/?id=e4a6d9f8b2c3f7c1d5e0a8b9c1e2d0f)

### 7 - [Improper Certificate Validation - JavaScript](https://leapfix.co/?id=5f4dcc3b5aa765d61d8327deb882cf99)

### 8 - [Improper Use of Cookies - PHP](https://leapfix.co/?id=a8d3d0d1be1d74e0b89d2ea8ad0d4685)

### 9 - [Insecure Communication - Dart](https://leapfix.co/?id=d5400fcef8873df0c253c4278a78d73b)

### 10 - [Potential SQL Injection in SELECT - ADVPL](https://leapfix.co/?id=01caea706a18eb8ec8d0126557d026eb)


### Inovation
LeapFix is ​​the only plugin in the world that performs static code analysis (SAST) in the ADVPL language.

## The LeapFix
The word Leap means to jump and fix means to correction vulnerabilities.
But the combination of Leap fix means a "quick fix".
This is exactly the purpose of plugin: to provide developers with the opportunity to look for vulnerabilities while developing their code, without needing web platforms to make them aware of the vulnerabilities.




## Contributing

**The plugin was created by [Fernando Mengali](https://www.linkedin.com/in/fernando-mengali-273504142/) and distributed through the company [fitoxs](https://fitoxs.com).**

## License

This project is licensed under the MIT License.
