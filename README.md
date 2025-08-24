# Bootstrap for Beginners

## Areas Covered
- [x] What is Bootstrap?
- [x] Installation / Setup
- [x] Grid System
- [x] Components 

### 1. What is Bootstrap?

- One of the Most popular front-end framework.
- Used for building responsive, mobile first websites and web applications.
- HTML / CSS / JavaScript

#### Why use Bootstrap?

- Increase development speed.
- Assure responsiveness.
- Prevent repitition  between projects
- Add consistency
- Ensure cross browser compatibility
- Large community
- Customizable.

#### Bootstrap components and helpers

| -------------- | -------------- |
- Alert
- Badges
- Breadcrumbs
- Buttons
- Cards
- Carousel
- Collapse
- Dropdowns
- List group
- Modal
- Navbars
- Panels
- Paginations
- Popovers
- Progress bars
- Scrollspy
- Spinners
- Toasts
- Tooltips
- Clearfix
- Icons
- Tables
- Responsive Utilities
- Gutters

### 2. Installation

Several quick start options are available:

- [Download the latest release](https://github.com/twbs/bootstrap/archive/v5.3.2.zip)
- Clone the repo: `git clone https://github.com/twbs/bootstrap.git`
- Install with [npm](https://www.npmjs.com/): `npm install bootstrap@v5.3.2`
- Install with [yarn](https://yarnpkg.com/): `yarn add bootstrap@v5.3.2`
- Install with [Composer](https://getcomposer.org/): `composer require twbs/bootstrap:5.3.2`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package bootstrap` Sass: `Install-Package bootstrap.sass`

Read the [Getting started page](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for information on the framework contents, templates, examples, and more.

**Install Popper js, Bootstrap works with it**
- Either use `npm` or `download` it.
- `npm install @popperjs/core --save`
- Or use the `<script src="./js/bootstrap.bundle.js"></script>` 

**Use CDN**

### 3. Bootstrap Grid System

- Column of 12 units
- Grid, Row and Columns
- Containers
- Breakpoints
- Media Queries
- Sizes
- `my-5` : Margin in the y-axis (top and bottom)
- `mx-5` : Margin in the x-axis (right and left)

### 4. Components

- [x] Gutters
- Gutters are the padding  between the columns, used to responsively space and align content in the Bootstrap grid system. 
- Gutters are responsible for the distance between the columns.
- **Can't use Gutter on Container**, Cutter is used on `.row`.
- `gy-4` : Gutter on y-axis
- `gx-5` : Gutter on x-axis

```html
<div class="container">
        <div class="row gx-5 gy-5">
            <div class="col-6"><div class="child">1</div></div>
            <div class="col-6"><div class="child">2</div></div>
            <div class="col-6"><div class="child">3</div></div>
            <div class="col-6"><div class="child">4</div></div>
        </div>
    </div>
```
  
- [x] **Buttons**

```html
<div class="container">
    <button type="button" class="btn btn-secondary">Secondary</button>
    <button type="button" class="btn btn-primary">Primary</button>
    <button type="button" class="btn btn-warning">Warning</button>
    <button type="button" class="btn btn-info">Info</button>
    <button type="button" class="btn btn-danger">Danger</button>
    <button type="button" class="btn btn-outline-dark">Dark</button>
    <button type="button" class="btn btn-outline-light">Light</button>
    </div>
```

- [x] Cards


- [x]  Typography
- Responsive Font sizes

- [x]  Images
- Responsive images

```html
<div class="container">
    <div style="width:50%; border:5px red solid;" >
        <img src="./blog4.jpg" alt="" class="img-fluid" >
    </div>
    <h1 class="my-5">Thumbnail</h1>
        <img src="./blog4.jpg" alt="" class="img-thumbnail w-25" >
</div>

    <h1 class="my-5">Alignmemnt</h1>
        <img src="./blog4.jpg" alt="" class="float-end w-25" >

    <div class="clearfix"></div>
    
        <img src="./blog4.jpg" alt="" class="d-block mx-auto w-25 rounded" >

<!-- Use `.clearfix` after float -->

```

```html
    <div class="clearfix"></div>
```

- Use `.clearfix` after float

- [x]  **Utilities**
- [ ]  **Tailwind CSS** is *utility-first* framework.
- [ ]  Bootstrap also has Utilities capabilities.

- Spacing utility
> Bootstap includes a wide range of shorthand responsive margin, padding and gap to modify an element's appearance.
>
> - Margin and Padding

- Border utilities
- Background utility
- Colors utility
- Sizing utility
- Position utility
- Display utility
- Flex utility
- Vertical align utility
- Float utility
- Interactions utility
- Opacity utility
- Overflow utility
- Shadow utility
- Text utility
- Visibility utility

- [x] **Tables**

- [x] **Alerts** 

- [x] **Toasts**

- [x] **Navs and Navbars**
- [ ] Tabs
- [ ] Pills
- [ ] Side Nav 

- [x] **Icons**

- [x] **Forms**

- [x] **Other Components**
- [x] Accordians
- [x] Badges
- [x] Breadcrumb
- [x] Button groups
- [x] Dropdowns
- [x] List groups
- [x] Modal
- [x] Popovers
- [x] Tooltip
- [x] Spinners
- [x] Progress
- [x] Scrollspy

[Landing Page Demo](./index.html)

[Free image resource](https://www.picsum.photos)


#### Publish the website
- [x] Use the command line of the project ``
- Install [MDB Go](https://www.mdbgo.com) using `npm install -g mdb-cli`
- Your page should be in `index.html`
- Type `mdb publish`
- Choose a package manager `npm`
- Make a package name e.g. `bootstrap tutorial`
- 


