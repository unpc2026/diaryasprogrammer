# PHP Behind The Scene

  ## PHP Code Execution via Web Server
  The process of how PHP works involves a user's browser, a web server (like Apache or Nginx), and the PHP interpreter. This interaction is a server-side process that generates HTML content to be sent back to the client's browser. 
  
  - The typical flow can be visualized in the following steps:
    1. User Request: A user enters a URL in their web browser or clicks a link, which sends an HTTP request for a specific file (e.g., index.php) to the web server.
    2. Web Server Receives Request: The web server receives the request and analyzes the file extension. If the file has a .php extension, the web server passes the file to the PHP interpreter.
    3. PHP Processes Script: The PHP interpreter (which contains the Zend Engine) processes the PHP code. During this stage, PHP may:
      1. Perform server-side logic and calculations.
      2. Interact with a database (e.g., MySQL) using SQL queries to fetch or store data.
      3. Communicate with external APIs or the server's file system.
    4. PHP Generates Output: After execution, the PHP interpreter generates an output, typically in the form of plain HTML or other content types like JSON or XML. All PHP code is removed in this output.
    5. Web Server Sends Response: The web server receives the generated HTML output from the PHP interpreter and sends it back to the user's browser as an HTTP response.
    6. Browser Renders Page: The user's web browser receives the HTML response and renders the complete, dynamic web page on the user's screen. The user never sees the underlying PHP source code, only the resulting HTML. 
    
  - Key Components
    + Web Browser (Client): Initiates the request and displays the final HTML output.
  Web Server (e.g., Apache): An intermediary that handles HTTP requests and responses, directing PHP files to the PHP interpreter.
    + PHP Interpreter (Processor): The core component that reads, parses, and executes the PHP code into machine-readable opcodes, ultimately generating output. [What is PHP and How PHP Interpreter Works](https://dev.to/patricia1988hernandez2/what-is-php-and-how-php-interpreter-works-38k8)
    + Database (e.g., MySQL): Stores and retrieves data as instructed by the PHP script. 
  This flow demonstrates that PHP is a server-side language, dynamically generating content before the final page is sent to the client. 

# Tutorial
- [Official Documentation PHP](https://www.php.net/manual/en/)
- [PHP Tutorial - W3Schools](https://www.w3schools.com/php/)
- [PHP 7 Tutorial - Tutorial Republic](https://www.tutorialrepublic.com/php-tutorial/)
- [Programmer Zaman Now : TUTORIAL PHP DASAR BAHASA INDONESIA](https://www.youtube.com/watch?v=TaBWhb5SPfc)
- [Laracast : PHP For Beginners - Complete Laracasts Course](https://www.youtube.com/watch?v=fw5ObX8P6as)
- [Kenapa Coding : TUTORIAL PHP TERLENGKAP UNTUK PEMULA DISINI](youtube.com/watch?v=IkD2y4ubFdw)
