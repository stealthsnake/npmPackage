## Getting started
-------------------
You would need to compile the sass file into CSS, then link your css into your html page.
```html
<head>
    ...
    <link rel="stylesheet" href="path/to/file/compiledcss.css">
    ...
</head>
```



## Css toggle checkbox
-------------------
You would need to to use the below html structure tags to get the correct render, by default the text is on the left of the toggle. check the code below to see


#### Code:
```html
<label class="theme-toggle-switch-container">
    <input type="checkbox">
    <span class="toggle-text">Allow Notification</span>
    <span class="toggle-switch"></span>
</label>
```

#### Output would be
![togglec](https://github.com/stealthsnake/npmPackage/blob/master/images/round_left.png?raw=true)

###  Text on right
To make the text on the right of the toggle to add css class "right-text" to the theme-toggle-switch-container

#### Code:
```html
<label class="theme-toggle-switch-container right-text">
    <input type="checkbox">
    <span class="toggle-text">Allow Notification</span>
    <span class="toggle-switch"></span>
</label>
```

####  Output would be
![toggle right](https://github.com/stealthsnake/npmPackage/blob/master/images/toggle_right.png?raw=true)
### Round toggle

by default the toggle do have round edged corners, to make them round add class "round" to "toggle-switch"

#### Code:

```html
 <label class="theme-toggle-switch-container">
    <input type="checkbox">
    <span class="toggle-text">Allow Notification</span>
    <span class="toggle-switch radius"></span>
</label>
```

####  Output would be
![round right](https://github.com/stealthsnake/npmPackage/blob/master/images/round_right.png?raw=true)
### Round toggle - text on the right

To make the text on the right of the toggle to add css class "right-text" to the theme-toggle-switch-container

#### Code:

```html
<label class="theme-toggle-switch-container right-text">
    <input type="checkbox">
    <span class="toggle-text">Allow Notification</span>
    <span class="toggle-switch radius"></span>
</label>
```

####  Output would be
![round left](https://github.com/stealthsnake/npmPackage/blob/master/images/round_left.png?raw=true)
