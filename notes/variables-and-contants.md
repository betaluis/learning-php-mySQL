# Variables and Constants

Variables are used to store data and called later on to access that piece of data. 

## How do you create a variable?

    <?php 
        $firstName
    ?>

- Variables must never start with numbers or specal characters.

- cammelCase

### Create a variable that stores your first name and echo to the browser.

    <?php 
        $firstName = "Dexter"; 
        
        echo $firstName;
    ?>

We can also output the variable inside an HTML template.

    <!DOCTYPE html>
    <html>
        <head>
            <title>PHP Tutorials</title> 
        </head>
        <body>
            <h1>User Profile Page</h1>
            <div><?php echo $name; ?></div>
        </body>
    </html>

Create another variable that stores your age:

    <?php 
        $age = "26"; 
        
        echo $age;
    ?>

## Constants

It's a different type of variable that can't be overwritten.

This is how you create a constant: 

    define('NAME', 'Steve');

    <div><?php NAME ?></div>