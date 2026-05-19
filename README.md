# xcrudReload!

## Overview

- This is the source of xcrudReload! 1.x.
- xcrudReload [Official website](https://www.xcrud.me).

## What is xCrud?

- [xCrud!](https://www.xcrud.me) is a **Crud Framework** (Crud)

**Steps to setup the local environment:**

- Clone the repository:

```bash
git clone https://github.com/xcrud/xcrud.git
```

- Go to the xcrud-reload folder:

```bash
cd xcrud-reload

Usage Example

<?php
    include('xcrud/xcrud.php');
    $xcrud = Xcrud::get_instance();
    $xcrud->table('your_table');
?>
<!DOCTYPE HTML>
<html>
<head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>Some page title</title>
</head>
 
<body>
 
<?php
    echo $xcrud->render();
?>
 
</body>
</html>


Copyright
---------------------
* (C) 2005 Open Source Matters, Inc. <https://www.xcrud.me>
* Distributed under the GNU General Public License version 2 or later
```
