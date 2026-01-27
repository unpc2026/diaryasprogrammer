# PHP Behind The Scene

## PHP Code Execution via Web Server (keywords : how php works with the web server or how php works diagram)
The process of how PHP works involves a user's browser, a web server (like Apache or Nginx), and the PHP interpreter. This interaction is a server-side process that generates dynamic content before the final output is sent to the user's browser. 

The typical flow can be visualized in the following steps:
1. User Request :  
A user enters a URL in their web browser or clicks a link, which sends an HTTP request for a specific file (e.g., index.php) to the web server.
2. Web Server Receives Request :  
The web server receives the request and examines the file extension (.php) to identify it as a PHP file. If the file is a static asset (like an image, CSS, or plain HTML file), the web server serves it directly to the browser.
3. Request Passed to PHP Interpreter :  
The web server does not process PHP code itself. Instead, it uses a Server API (SAPI) like FastCGI, CGI, or mod_php to pass the request and the PHP file to the PHP interpreter (or PHP engine).
4. PHP Code Execution :  
The PHP interpreter reads and executes the script line by line through stages called Lexing, Parsing (PHP Parser), Compilation, and Interpretation/Execution. During the Execution stage, PHP can perform various tasks such as :
- Perform server-side logic and calculations.
- Process form data
- Interact with a database (e.g., MySQL) using SQL queries to fetch/retrieve/store data.
- Communicate with external APIs or the server's file system.
5. Output Returned to Web Server :  
Once execution is complete, the PHP interpreter sends the generated output (pure HTML, JSON, etc.) back to the web server. All PHP code is removed in this output.
6. Web Server Sends Response :  
The web server receives the generated output from the PHP interpreter and sends it back to the user's browser as an HTTP response.
7. Browser Renders Page :  
The user's web browser receives the HTML response and renders the complete dynamic web page on the user's screen. The user's browser never sees the underlying PHP source code, only the resulting HTML, CSS, or other content. 
    
Key Components :
+ Web Browser (Client): Initiates the request and displays the final HTML output.
+ Web Server (e.g., Apache): An intermediary that handles HTTP requests and responses, directing PHP files to the PHP interpreter.
+ PHP Interpreter (Processor): The core component that reads, parses, and executes the PHP code into machine-readable opcodes, ultimately generating output. [What is PHP and How PHP Interpreter Works](https://dev.to/patricia1988hernandez2/what-is-php-and-how-php-interpreter-works-38k8)
+ Database (e.g., MySQL): Stores and retrieves data as instructed by the PHP script.  
  
This flow demonstrates that PHP is a server-side language, dynamically generating content before the final page is sent to the client. This approach ensures that sensitive server-side logic and database interactions remain hidden from the client (enhancing security).

# PHP Basics

## PHP Linefeeds/Newline
When the PHP interpreter encounters a closing ?> tag, it generally switches back to "HTML mode," meaning any subsequent text (including whitespace and new lines) is output directly. However, there's a specific exception for the single linefeed (or newline) character that directly follows the closing tag. PHP "eats" this newline to prevent accidental unwanted output. 

Example 1 : The linefeed is removed
```php
<?php echo "Hello"; ?>
World
```

Output:
HelloWorld
The linefeed after ?> is removed, so "World" appears on the same line as "Hello". 

Example 2 : The linefeed is kept (due to an extra space)
```php
<?php echo "Hello"; ?> 
World
```
Output:
Hello World
Here, a space was added after ?> before the linefeed. PHP does not remove the linefeed if there is any other character (like a space) in between. 

This behavior is particularly useful in two scenarios :
- Included files: It helps prevent accidental blank lines from appearing when including files that end with a PHP block, especially if the intention is to not output anything (e.g., configuration files, functions libraries).
- Preventing "headers already sent" errors: Extra whitespace output before the main HTML content can cause errors when trying to set HTTP headers (like redirects or cookies) later in the script's execution. Removing the trailing newline avoids this common issue. 

This behavior is a primary reason why the official PHP documentation recommends omitting the closing ?> tag entirely for files that contain only PHP code


# Tutorial
- [Official Documentation PHP](https://www.php.net/manual/en/)
- [PHP Tutorial - W3Schools](https://www.w3schools.com/php/)
- [PHP 7 Tutorial - Tutorial Republic](https://www.tutorialrepublic.com/php-tutorial/)
- [Programmer Zaman Now : TUTORIAL PHP DASAR BAHASA INDONESIA](https://www.youtube.com/watch?v=TaBWhb5SPfc)
- [Laracast : PHP For Beginners - Complete Laracasts Course](https://www.youtube.com/watch?v=fw5ObX8P6as)
- [Kenapa Coding : TUTORIAL PHP TERLENGKAP UNTUK PEMULA DISINI](youtube.com/watch?v=IkD2y4ubFdw)
