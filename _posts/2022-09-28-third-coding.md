---
layout: post
title:  "Third coding of the game"
date:   2022-09-28 19:45:35 +0900
categories: Study
---

##How to set for the actual game playing

```js
class MainActivity : AppCompatActivity() {

    lateinit var startbutton : Button
    lateinit var titleTextView : TextView


    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        println("@@@@@onCreate")

        startbutton = findViewById(R.id.button2)



        startbutton.setOnClickListener {
            findViewById<ImageView>(R.id.imageView).visibility = View.GONE

        }

        val myCar = Car()
        myCar.color = "red"
        myCar.model = "Lamborghini"
        myCar.accelerate(200)
        myCar.brake()
        myCar.paintmyCar( "yellow")





    }
    override fun onStart() {
        super.onStart()

        println("@@@@@@@@@@onStart")
        println("@@@ONSTART")

    }

    override fun onResume() {
        println("@@@@@onResume")
        super.onResume()

    }

    override fun onPause() {
        println("@@@@@onPause")
        super.onPause()
    }

    override fun onDestroy() {
        println("@@@@@onDestroy")
        super.onDestroy()
    }

    override fun onStop() {
        println("@@@@@onStop")
        super.onStop()
    }

}
```