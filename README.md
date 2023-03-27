# environment variables

1. create a file at the rrot of the project
```
.env
```

2. inside the env. file add the text:
- you must use `NEXT_PUBLIC` or else this wwill not work

```
NEXT_PUBLIC_TITLE = "digital design ad development diploma"
``` 

3. on the page, in between the export and return write the variables:
```
var title = process.env.NEXT_PUBLIC_TITLE
```

4. then in between the main write:
```
(title)
```

5. make sure the `.gitignore` file has the `.env` file inside
- you want to prevent this secrete title to be shown

# BCIT Data from Digital Design and Development Diploma
[Digital Design and Development Diploma](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/)