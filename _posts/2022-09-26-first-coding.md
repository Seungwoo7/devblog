---
layout: post
title:  "First coding of the game"
date:   2022-09-26 19:45:35 +0900
categories: Study
---

##How to add buttons and text/set position

```js
<TextView
        android:id="@+id/tv_main_title"
        android:layout_width="122dp"
        android:layout_height="30dp"
        android:layout_margin="20dp"
        android:gravity="center"
        android:text="Hi! I'm Seungwoo "
        android:textSize="15sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintTop_toBottomOf="@+id/imageView"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintVertical_bias="0.1"
         />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="LIKE"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tv_main_title"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.35"

        />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="HATE"
        android:textColor="@color/white"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/tv_main_title"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintHorizontal_bias="0.65"

        />
```




##How to add colors

```js

  <?xml version="1.0" encoding="utf-8"?>
<resources>
    <color name="purple_200">#FFBB86FC</color>
    <color name="purple_500">#FF6200EE</color>
    <color name="purple_700">#FF3700B3</color>
    <color name="teal_200">#FF03DAC5</color>
    <color name="teal_700">#FF018786</color>
    <color name="black">#FF000000</color>
    <color name="white">#FFFFFFFF</color>
    <color name="green"></color>
    <color name="red"></color>
</resources>
```
