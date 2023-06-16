# Browser Utils Plugin

Open the URL where the cursor is on.

## To initiate the function

Fisrt. Place the cusor on or ahead of the target link URL,  
Then run:

```
> browse
```

## To open URL with a cusom command

{URL} in option string will be replaced with true URL value  
Run to set cmd option:

```
> set browser.cmd "yourCustomCommand"
```

An example to open URL with chrome in incognito:

```
> set browser.cmd "path/to/chrome/executable -incognito {URL}"
```

Reset to default:

```
> set browser.cmd "default"
```
