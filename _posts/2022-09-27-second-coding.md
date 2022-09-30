---
layout: post
title:  "Second coding of the game"
date:   2022-09-27 19:45:35 +0900
categories: Study
---

##How to add image

```js
 <ImageView
        android:id="@+id/imageView"
        android:layout_width="0dp"
        android:layout_height="0dp"
     app:layout_constraintStart_toStartOf="parent"
     app:layout_constraintEnd_toEndOf="parent"
        android:layout_margin="100dp"
        app:layout_constraintDimensionRatio="1:1"
        app:layout_constraintTop_toTopOf="parent"
       android:src="@drawable/ic_picasso_description"
        />
```

##How to understand the relationship between values with example

```js

class Car {

    var color : String = ""
    var model : String = ""
    var speed : Int = 0

    fun accelerate(maxSpeed : Int){
        //acceleration
        speed = maxSpeed
    }
    fun brake() {
     speed = 0

    }

    fun paintmyCar(color : String) {
        this.color = color

    }

}

```