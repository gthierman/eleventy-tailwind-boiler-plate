# Eleventy boilerplate with Tailwind and optional Alpine.js

## Basic setup
Install dependencies:
```
npm install
```

Run the code:
```
npm start
```

## Disable Alpine.js
To disable alpine.js open `.eleventy.js` and search for 
```
eleventyConfig.addGlobalData("alpinejs", true);
```

Change `true` to `false`
```
eleventyConfig.addGlobalData("alpinejs", false);
```