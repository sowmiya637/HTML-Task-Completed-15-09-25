#  Hyperlinks, Images, Media, and Navigation

HTML webpage demonstrating various **hyperlink techniques**, **image embedding**, **downloadable media**, **favicons**, **image maps**, and **basic navigation**. 

### 1. **Favicon**
Displays a small icon in the browser tab using:

```html
<link rel="icon" type="image/svg+xml" href="images/img3.svg">

### 2. **Background Image**

Uses a full-screen background image via CSS:

body {
  background-image: url("https://data.ipic.ai/images/nHqPG57WgjAEVvr_1718588853.webp");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

### 3. **Types of Hyperlinks**

 External Link: Opens another website
 New Tab: target="_blank"
 Mail Link: Opens email client
 Phone Call: Triggers dialer
 In-page Navigation: Using ID and anchor
 Download Link: For images and videos

<a href="https://www.google.com" target="_blank">Visit Google</a>
<a href="mailto:someone@example.com">Email Us</a>
<a href="tel:+9788123456">Call Us</a>
<a href="#about">Jump to About Section</a>
<a href="images/video1.mp4" download>Download Video</a>

### 4. **Navigation Bar**

Simple HTML navigation using <nav>:

<nav>
  <a href="/home">Home</a>
  <a href="/about">About</a>
  <a href="/contact">Contact</a>
</nav>

### 5. **Image Embedding Techniques**

Local Image
External Image
Responsive Image
Multiple Formats with <picture> tag

<img src="images/img3.svg" alt="A description" width="300" height="200">
<picture>
  <source srcset="images/img1.webp" type="image/webp">
  <source srcset="images/img2.jpg" type="image/jpeg">
  <img src="images/img3.svg" alt="Sample">
</picture>

### 6. **Image Map**

An image with clickable areas using <map> and <area>:

<map name="image_mapping">
  <area shape="rect" coords="50,50,150,150" href="https://www.geeksforgeeks.org/" title="Windows">
  <area shape="circle" coords="300,200,50" href="https://www.google.com" title="Google">
</map>

### 7. **Floating Image**

Wraps text around an image using float: left:

<img src="images/img3.svg" style="float: left; width: 100px;">
<p>This is a paragraph that wraps around the image.</p>
