# Pink Portfolio

A responsive personal portfolio website built with HTML and CSS.

## About

This project is a simple and elegant personal portfolio with a soft pink visual style. It is designed mainly for mobile screens but also adapts to larger screens.

The portfolio includes a profile picture, a name, a short introduction, social media buttons, and an email contact button.

## Project Structure

```text
pink-portfolio/
├── index.html
├── style.css
├── README.md
├── backgroundpic.png
└── assets/
    ├── creator.png
    ├── instagram.png
    ├── tiktok.png
    ├── youtube.png
    └── gmail.png
```

## Files Explained

### `index.html`

This is the main page of the portfolio.

It contains:
- the profile picture
- the name
- the biography or short introduction
- the Instagram button
- the TikTok button
- the YouTube button
- the Email button

If you want to change the text, account links, or email address, this is the main file you will edit.

### `style.css`

This file controls the design of the portfolio.

It contains:
- the pink and white colors
- fonts
- button sizes
- profile picture shape
- spacing
- shadows
- mobile layout
- background styling

If you want to change the appearance of the website, edit this file.

### `backgroundpic.png`

This is the background image used on the website.

To replace it:

1. Choose a new background image.
2. Rename the new image to:

```text
backgroundpic.png
```

3. Put it in the main project folder, next to `index.html` and `style.css`.
4. Replace the old `backgroundpic.png`.

If you want to use a different filename, change the filename inside `style.css`.

For example:

```css
background: url("mybackground.png") center / cover no-repeat;
```

## Images in the `assets` Folder

All the main pictures and icons are stored inside the `assets` folder.

### `creator.png`

This is the profile picture.

To change it:

1. Choose the profile picture you want to use.
2. Rename it to:

```text
creator.png
```

3. Put it inside the `assets` folder.
4. Replace the old `creator.png`.

The website will automatically use the new image.

If your picture is a JPG instead, for example `creator.jpg`, change this line in `index.html`:

```html
src="assets/creator.png"
```

to:

```html
src="assets/creator.jpg"
```

### `instagram.png`

This is the image shown inside the Instagram button.

To change it, replace the file inside `assets` with another image named:

```text
instagram.png
```

### `tiktok.png`

This is the image shown inside the TikTok button.

To change it, replace the file inside `assets` with another image named:

```text
tiktok.png
```

### `youtube.png`

This is the image shown inside the YouTube button.

To change it, replace the file inside `assets` with another image named:

```text
youtube.png
```

### `gmail.png`

This is the image shown inside the Email button.

To change it, replace the file inside `assets` with another image named:

```text
gmail.png
```

## How to Add Your Social Media Links

Open `index.html` in VS Code.

You will find buttons that look similar to this:

```html
<a
  class="platform-button"
  href="https://www.instagram.com/"
  target="_blank"
  rel="noopener noreferrer"
>
```

Replace the URL inside `href=""` with your own account link.

### Instagram

Change:

```html
href="https://www.instagram.com/"
```

to something like:

```html
href="https://www.instagram.com/yourusername/"
```

### TikTok

Change:

```html
href="https://www.tiktok.com/"
```

to:

```html
href="https://www.tiktok.com/@yourusername"
```

### YouTube

Change:

```html
href="https://www.youtube.com/"
```

to your own YouTube channel link.

For example:

```html
href="https://www.youtube.com/@yourusername"
```

## How to Change the Email Button

Find the Email button inside `index.html`.

It will look similar to this:

```html
<a
  class="platform-button"
  href="mailto:creator@email.com"
>
```

Replace:

```text
creator@email.com
```

with your own email address.

For example:

```html
href="mailto:hello@example.com"
```

When someone presses the Email button, their email application will open with your email address ready.

## How to Change the Name

Inside `index.html`, find:

```html
<div class="creator-name">
  name of creator
</div>
```

Replace the text with your own name.

For example:

```html
<div class="creator-name">
  Sarah
</div>
```

## How to Change the Introduction

Inside `index.html`, find the paragraph with:

```html
<p class="creator-bio">
```

Replace the text inside it with your own introduction.

For example:

```html
<p class="creator-bio">
  Welcome to my personal portfolio.
</p>
```

## Important Image Tips

- Keep all images inside the correct folder.
- Make sure the filename in `index.html` matches the actual filename exactly.
- GitHub is case-sensitive, so `Instagram.png` and `instagram.png` are not the same filename.
- PNG images with transparent backgrounds usually work best for the social media icons.
- A square image works best for the profile picture because it is displayed as a circle.

## How to Preview the Website in VS Code

If you use the Live Server extension:

1. Open the project folder in VS Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.
4. The website will open in your browser.

## Publishing with GitHub Pages

After uploading the project to GitHub:

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch.
6. Select `/ (root)`.
7. Save the settings.

GitHub will create a public website link for the portfolio.

## Technologies

- HTML5
- CSS3
