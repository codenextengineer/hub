# Project Guide
## Fan/Business Page

<p>Use your knowledge of mobile user interfaces to build a single-screen app</p>
<p>Your app can display information about anything you are a fan of (like a TV show, book, Coach Wolf, etc), or a small business/organization (can be fictional, or even Code Next)</p>

<p>Your app should AT LEAST include:</p>
<ul>  
  <li>The name of what it's about</li>
  <li>An image (or multiple images)</li>
  <li>A description (could include contact info for a business)</li>
</ul>

## Getting Started 

#### Open Android Studio & click "Start a new Android Studio project"

![](guide-images/open.png)

#### Give your app a name

![](guide-images/configure.png)

#### Choose "API 15..." as the Minimum SDK

![](guide-images/target-device.png)

#### Choose the Empty Activity template

![](guide-images/empty.png)

#### Click "Finish"

![](guide-images/finish.png)

#### Replace all of the code in "activity_main.xml" with starter layout code

![](guide-images/highlight.png)<br>
![](guide-images/replace.png)

Starter Layouts:

[Scrolling LinearLayout](../starter-layouts/scrollview-starter.xml)<br>
[LinearLayout](../starter-layouts/linear-starter.xml)<br>
[RelativeLayout](../starter-layouts/relative-starter.xml)<br>

## Adding images

#### Download an image and rename it to something simple

![](guide-images/pic.png)

#### Copy the image (Command + C)

![](guide-images/copy.png)

#### Choose the "drawable" folder in Android Studio and paste the image (Command + V)

![](guide-images/paste.png)

#### Press "Ok"

![](guide-images/ok.png)

#### In the "android:src" attribute, add the image with "@drawable/your-image-name"

![](guide-images/imageview.png)
