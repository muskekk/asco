[site](https://muskekk.github.io/asco/)

# ASCO

ASCO is a browser-based ASCII art generator for creating 3D text, image, and video ASCII art.

## How to Use

### Text

The **Text** tab is the main 3D ASCII generator.

Enter any text into the input field.

Example:

~~~text
ASCO
~~~

ASCO converts the text into a 3D ASCII object.

### 3D Controls

You can customize the generated 3D text with the following controls:

- **Font Size** — Changes the size of the original text.
- **Depth** — Controls the depth of the 3D object.
- **Zoom / Scale** — Changes the size of the ASCII output.
- **Rotate X** — Rotates the object vertically.
- **Rotate Y** — Rotates the object horizontally.
- **Rotate Z** — Rotates the object around its center.

### Mouse Controls

You can control the 3D object directly with your mouse.

- **Click + Drag** — Rotate the object.
- **Scroll Up** — Zoom in.
- **Scroll Down** — Zoom out.

### Animation

Click **Animate** to automatically rotate the 3D ASCII text.

Click **Stop Anim** to stop the animation.

---

## Image

The **Image** tab converts an image into ASCII art.

Select an image using the upload field.

Once an image is selected, ASCO automatically processes it and displays the ASCII result.

### Image Settings

#### Width

Controls the width of the generated ASCII image.

A larger width produces more detailed ASCII art.

#### Gamma

Controls the brightness mapping of the image.

Adjust the value until the image has the desired contrast.

#### Invert

Controls the brightness direction.

- **Normal** — Uses the normal brightness mapping.
- **Inverted** — Reverses the brightness mapping.

#### Charset

ASCO provides several character styles.

- **Standard** — A balanced ASCII character set.
- **Detailed** — Uses many characters for higher detail.
- **Blocks** — Uses block characters for a stronger appearance.
- **Minimal** — Uses a smaller character set.
- **Hex** — Uses hexadecimal characters.

Try different character sets to create different visual styles.

---

## Video

The **Video** tab converts video frames into ASCII art in real time.

Select a video file and click **Start**.

ASCO processes the video frame by frame and displays the result as ASCII art.

Click **Stop** to stop processing.

### Video Settings

#### Width

Controls the width of the ASCII video.

A smaller width requires less processing power.

#### FPS

Controls how many frames are processed per second.

For example:

~~~text
12 FPS
~~~

Higher FPS produces smoother animation but requires more processing power.

#### Gamma

Controls the brightness mapping of the video.

#### Charset

The video generator supports:

- **Standard**
- **Detailed**
- **Blocks**

---

## Webcam

ASCO can also convert your webcam feed into ASCII art.

Open the **Video** tab and click **Webcam**.

Your browser will ask for permission to access the camera.

Allow camera access and then click **Start**.

The webcam feed will be converted into ASCII art in real time.

Click **Stop** to stop the webcam ASCII output.

---

## Copying ASCII Art

After generating ASCII art, click **Copy**.

The current ASCII output will be copied to your clipboard.

You can paste the result into any text editor, terminal, website, chat application, or other supported application.

---

## Tips

### 3D Text

For a stronger 3D effect:

- Increase **Depth**.
- Adjust **Rotate X** and **Rotate Y**.
- Use mouse dragging to quickly find the desired angle.
- Increase **Zoom / Scale** if the output is too small.
- Use **Animate** to create a rotating ASCII object.

### Images

For more detailed image ASCII art:

- Increase **Width**.
- Adjust **Gamma**.
- Try the **Detailed** charset.
- Use **Invert** when the normal brightness mapping does not look good.

### Videos

For better performance:

- Reduce the **Width**.
- Reduce the **FPS**.
- Use a simpler charset such as **Standard**.
- Avoid extremely large video resolutions.

---

## Controls

| Control | Description |
|---|---|
| Text | Create 3D ASCII text |
| Image | Convert images into ASCII art |
| Video | Convert videos into ASCII art |
| Webcam | Convert webcam video into ASCII art |
| Font Size | Change the 3D text size |
| Depth | Change the 3D extrusion depth |
| Zoom / Scale | Change the ASCII output scale |
| Rotate X | Rotate the object vertically |
| Rotate Y | Rotate the object horizontally |
| Rotate Z | Rotate the object around its center |
| Animate | Automatically rotate the 3D object |
| Stop Anim | Stop the 3D animation |
| Copy | Copy the generated ASCII art |
| Start | Start video or webcam processing |
| Stop | Stop video or webcam processing |

---

## Browser Requirements

ASCO works in modern browsers.

Recommended browsers:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

Webcam functionality requires browser permission to access the camera.

---

## Project

ASCO is built with standard web technologies:

- HTML
- CSS
- JavaScript
- HTML Canvas API
- Web Camera API
- Clipboard API

No framework is required to run the main application.

