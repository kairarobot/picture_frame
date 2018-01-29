# Picture Frame

An implementation of CSS to emulate a picture frame hanging on the wall.
The bottom border has the lightest hue, the left and right borders have 
medium hues, and the top border has the darkest hue.

To apply this frame to an element, add the class "frame" in your HTML
document and attach the snippet below to your style sheet.

```
.frame {
    background-color: #d3dadd;
    border: solid 4vmin #847f95;
    border-bottom-color: #847f95;
    border-left-color: #716c85;
    border-radius: 2px;
    border-right-color: #716c85;
    border-top-color: #565268;
    box-shadow: 0 0 20px 0 rgba(0,0,0,.50) inset, 0 5px 10px 5px rgba(0,0,0,.50);
}
```

![pictureframe](https://github.com/kairaygun/picture_frame/blob/master/picture_frame_mock.png)
