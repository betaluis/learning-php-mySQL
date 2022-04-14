# Creating Your First PHP File

1. Create this directory:  ~/xampp/htdocs/tuts

2. Open the tuts folder in your code editor.

3. Create file within the folder called `index.php`.

To be able to write PHP code you'll have to place code within the PHP tags.

    <?php
        ...my awesome php code. 
    >

First PHP statement:

    echo 'hello, world!';

- In PHP, you have to add semicolon at the end of the statement.
- `Echo` is rendering whatever is passed in and returning as a an html document with the string "Hello, world!" inside of it 

## How to embed PHP code insdie HTML

You can create HTML templates inside php files.

    <!DOCTYPE html>
    <html>
        <head>
            <title>My first PHP file</title> 
        </head>
        <body>
            <h1><?php echo 'hello, world!; ?></h1> 
        </body>
    </html>