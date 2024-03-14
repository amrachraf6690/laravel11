## <h1 align="center">Fixing Migration Error</h1>

The issue happens when you try to migrate at mySql


# Error:

![image](https://github.com/amrachraf6690/laravel11/assets/78552764/139150d9-cde1-4b67-aa2e-1670791d2138)

# Fixing:

# <h4 align="center">Method 1</h4>
-> Go to config/database.php search for connections.mysql.collation / To fix the problem is to change utf8mb4_0900_ai_ci to the collation that is compatable for you.


# <h4 align="center">Method 2</h4>
-> Go to .env and add this 'DB_COLLATION=utf8mb4_unicode_ci' below the DB_PASSWORD (Note: change utf8mb4_unicode_ci to the collation that is compatable for you. )

