# Backend


## PHP


### PHP Behind The Scene

- PHP Code Execution via Web Server (keywords : how php works with the web server or how php works diagram)  

  The process of how PHP works involves a user's browser, a web server (like Apache or Nginx), and the PHP interpreter. This interaction is a server-side process that generates dynamic content before the final output is sent to the user's browser.

  - The typical flow can be visualized in the following steps:
    1. User Request :  
       A user enters a URL in their web browser or clicks a link, which sends an HTTP request for a specific file (e.g., index.php) to the web server.
    2. Web Server Receives Request :  
       The web server receives the request and examines the file extension (.php) to identify it as a PHP file. If the file is a static asset (like an image, CSS, or plain HTML file), the web server serves it directly to the browser.
    3. Request Passed to PHP Interpreter :  
       The web server does not process PHP code itself. Instead, it uses a Server API (SAPI) like FastCGI, CGI, or mod_php to pass the request and the PHP file to the PHP interpreter (or PHP engine).
    4. PHP Code Execution :  
       The PHP interpreter reads and executes the script line by line through stages called Lexing, Parsing (PHP Parser), Compilation, and Interpretation/Execution. During the Execution stage, PHP can perform various tasks such as :
       1. Perform server-side logic and calculations.
       2. Process form data.
       3. Interact with a database (e.g., MySQL) using SQL queries to fetch/retrieve/store data.
       4. Communicate with external APIs or the server's file system.
    5. Output Returned to Web Server :  
       Once execution is complete, the PHP interpreter sends the generated output (pure HTML, JSON, etc.) back to the web server. All PHP code is removed in this output.
    6. Web Server Sends Response :  
       The web server receives the generated output from the PHP interpreter and sends it back to the user's browser as an HTTP response.
   7. Browser Renders Page :  
       The user's web browser receives the HTML response and renders the complete dynamic web page on the user's screen. The user's browser never sees the underlying PHP source code, only the resulting HTML, CSS, or other content. 
    
  - Key Components
    + Web Browser (Client): Initiates the request and displays the final HTML output.
    + Web Server (e.g., Apache): An intermediary that handles HTTP requests and responses, directing PHP files to the PHP interpreter.
    + PHP Interpreter (Processor): The core component that reads, parses, and executes the PHP code into machine-readable opcodes, ultimately generating output. [What is PHP and How PHP Interpreter Works](https://dev.to/patricia1988hernandez2/what-is-php-and-how-php-interpreter-works-38k8)
    + Database (e.g., MySQL): Stores and retrieves data as instructed by the PHP script.  
  
  This flow demonstrates that PHP is a server-side language, dynamically generating content before the final page is sent to the client. This approach ensures that sensitive server-side logic and database interactions remain hidden from the client (enhancing security).

  - Tutorial
    + [Official Documentation PHP](https://www.php.net/manual/en/)
    + [PHP Tutorial - W3Schools](https://www.w3schools.com/php/)
    + [PHP 7 Tutorial - Tutorial Republic](https://www.tutorialrepublic.com/php-tutorial/)
    + [Programmer Zaman Now : TUTORIAL PHP DASAR BAHASA INDONESIA](https://www.youtube.com/watch?v=TaBWhb5SPfc)
    + [Laracast : PHP For Beginners - Complete Laracasts Course](https://www.youtube.com/watch?v=fw5ObX8P6as)
    + [Kenapa Coding : TUTORIAL PHP TERLENGKAP UNTUK PEMULA DISINI](youtube.com/watch?v=IkD2y4ubFdw)
