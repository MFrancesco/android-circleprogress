# android-circleprogress

A simple progress indicator on a circle.

![Screen](https://github.com/kratorius/android-circleprogress/raw/master/demo/images/showcase.png)


## Requirements

* API 9+


## Getting started

Just add the library to your project and add a view like this:

``` xml
        <com.github.kratorius.circleprogress.CircleProgressView
            android:id="@+id/crc_standard"
            android:layout_width="150dp"
            android:layout_height="150dp"
            android:layout_gravity="center"
            circle:value="75" />
```

For more examples, check the [demo project](https://github.com/kratorius/android-circleprogress/tree/master/demo).


## Available view properties

* `thickness`: controls the thickness of the circle
* `color`: the color of the circle
* `value`: the "progress" (in the 0-100 range)
* `startAngle`: starting angle
* `text`: optional text inside the circle
* `textColor`: above text's color
* `textSize`: above text's size
* `startAnimation`: one of `none`, `roll`, `fadeIn`, `incremental`, `thicknessExpand`.

[![Analytics](https://ga-beacon.appspot.com/UA-184881-14/android-circleprogress)](https://github.com/igrigorik/ga-beacon)
