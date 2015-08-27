#img-resizable  

The `img-resizable` extension gives a resizable property to a standard `img` tag.  
When dragging the image it will be resized (maintaing aspect ratio) according to the image position.    
For Polymer 1.0 (fixin it atm).      

### Install  
From bower:    
`bower install mazzaaaaa/img-resizable`

### Usage  
```html
<img is="img-resizable" src="https:aaa.jpeg" downsizable restorable cursor>
```

The following attributes are supported:     
- `position`: The position of the image relative to the container.  
  One of:    
   - `left`: image will be resized dragging to the right.    
  - `right`: image will be resized dragging to the left.    
- `downsizable`: If true, the image can be resized below the original size.  
- `restorable`: If true, the image can be restored to the orifinal size with a double tap.
- `cursor`: If true, the cursor will change during the resizing of the image.

### Demo
<a href="http://mazzarolomatteo.com/polymer/img-resizable-demo/">Demo</a>
