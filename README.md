# Deploy on Day One

Every time a new semester begins their journey through Learn, their first project is to create their own student profile page. We have already created a template, but you need to use your Git, HTML and CSS skills to submit an updated version of the site with your information.

## Requirements

Please collect the following content from your assigned student for their profile. This content doesn't have to be finalized, but you need something. They'll be using this content as the project evolves for their resume and other profiles online.

* Name
* Blog Url (if you have one)
* Twitter URL
* LinkedIn URL
* Github URL
* Tagline
* Profile Picture (something normal, a headshot, of a good reusable size that can be easily cropped)
* Background Picture (like your cover picture from Twitter)
* Previous Work Experience
* Short Bio
* Education

## Structure

The structure of this project looks something like this:

```text
├── README.md
├── css
│   ├── css style sheets
├── assets
|   |__ img
|   |   ├── lots of images
|   |__ fonts
|   |   ├── some fonts
├── index.html
├── profile.html
└── students
    └── student-name.html
```

### Files you will need to alter:
  * `index.html`
  * `css/styles.css`
  * `students/student-name.html`

### Files you will need to add:
  * Add two pictures to the `img` folder (they can be jpg or png files):
    * A cover picture (named `student-name-cover.jpg/png`)
    * A profile picture (name `student-name.jpg/png`)
  * Add one HTML file to the `students/` folder. Use the other profiles or `profile.html` for reference. In fact, feel free to copy as much of the HTML from `profile.html` into the new file you've created (just don't rename / override that file, as that will cause you some git headaches).

## Getting Started

Fork and clone this lab.

### Individual Instructions

Now that you have everything locally, let's take stock of what we have. Take a look at `index.html` and `profile.html` in the browser. You can do this many ways but one is by opening finder and right clicking on `index.html`. Then click on "Open with" then the name of your favorite browser. The other is in terminal just typing `open index.html`.

#### Add Profile

  1. Copy the `profile.html` file into the `students` directory and rename it `your-name.html`. 
  2. Add in your cover and profile photo to the `img` directory
  3. Open up `your-name.html` and modify it with your information.
     * Adding the images is a bit tricky! Take a look at the `styles.css` or use inspect element for an idea of where those images come from.

#### Add To The Index

  1. Open up `index.html`
  2. copy one of the existing `div`s to make a new slot for you. Add in your information
  3. Re-use the profile image from your profile page and link to your profile page

#### Submit!

  1. Submit a Pull Request back to us.
