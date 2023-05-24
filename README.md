# Date Picker
This is a that picker that created with react.js.

## How to use?
Use DatePicker component like this:

```jsx
import React from "react";
import DatePicker from "./DatePicker";

const App = () => {
    return (
        <DatePicker until="80" type="jalali" theme="purple" />
    )
}

export default App
```

**until:** Number of years you want to be supported. For example ***until=10*** means until 10 years ago from this year.

- theme
	- purple
	- blue
	- yellow
	
+ type
	- jalali
	- gregorian

## Gallery
![date-picker-image-1](https://github.com/MJF1382/date-picker/blob/main/images/Resume_1.png)
![date-picker-image-2](https://github.com/MJF1382/date-picker/blob/main/images/Resume_2.png)
![date-picker-image-2](https://github.com/MJF1382/date-picker/blob/main/images/Resume_3.png)
