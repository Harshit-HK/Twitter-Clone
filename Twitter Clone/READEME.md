
__Run the following commands to start the project:__

```
npm i

This is notNow run your live preview.
```

# Setup Tailwind CSS for this Project

Step 1: Run the following commands

``` 
npm init -y
npm install -D tailwindcss@3
npx tailwindcss init
```

Step 2: Update tailwind.config.js file to include this line:
```
content: ["*.html"],
```

Step 3: create css/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```

Step 4: Run the following command to go online in Tailwind CSS:
```
npx tailwindcss -i ./css/input.css -o ./css/output.css --watch
```

Step 5: Include the css/output.css file to your html

```
  <link rel="stylesheet" href="src/output.css">

```
