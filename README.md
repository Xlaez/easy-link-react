This project is the react frontend for the connect app.

### Connect

- Makes use of react 18
- Makes use of redux
- Makes use of styled-components

Note: As you add new tools make sure to add it to this readme.

### Steps

- Design of login/ registration pages
- Design of user feed
- Design of messenger and conferencing app
- Api Integration

### Color Scheme

```HTML
    <button style="background='#0a66c1', color='#fff', padding='10px 20px'"></button>
```

- #000000 -- secondary color
- #0a66c1 -- primary colorstyle
- #fff -- tertiary/neutral color
- #040412 -- xtra color

### Code choices

- use of rem over px's except in styling of buttons and minor elements like buttons
- use of flex over grid when the proportionality of to-be-grid elements is not neccessary
- use grid to enforce elements stay in place
- avoid floats
- use vh/vw in setting width's and heights of a page for resposiveness
- for each component created, mobile and tablet view should be immediately implemented before designing another component
- use of cookies over localStorage

### Design

- Login Page

* user log's in with email and password as primary option
* a button that says signin with linkedIn . Note: only linkedIn not google and facebook
