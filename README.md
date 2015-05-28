#img-resizable

The `img-resizable` extension gives a resizable property to a standard `img` tag.
When dragging the image it will be resized (maintaing aspect ratio) according to the image position.  
For Polymer 0.9.    

### Install  
to-do  

### Usage
```html
`<img is="img-resizable" src="https:aaa.jpeg" downsizable restorable cursor>`
```

The following attributes are supported:   
- `position`: The position of the image relative to the container.
		One of:  
			`left`: image will be resized dragging to the right.  
			`right`: image will be resized dragging to the left.  
- `downsizable`: If true, the image can be resized below the original size.  
- `restorable`: If true, the image can be restored to the orifinal size with a double tap.
- `cursor`: If true, the cursor will change during the resizing of the image.

### Demo
To-do

### Contacts
Email: Mazzarolomatteo@gmail.com