--- 
title: Two Blog Posts. 
date: 2021-3-19
---

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## What is Frontend Development? 

Frontend Development is essentially the stuff you see. It's also known as client-side development. It deals with the stuff that the average user will be interacting with. The applications, the user-interface, the text- I think you get the idea. The challenge with client-side development is developing an easy to use format, application, and user-interface (essentially anything the user actively interacts with) that anyone can easily interact with and use. 

## Reflection on Learning.

We've been working on Frontend Development for several weeks! Our Pinboard Project! We had to work on interfaces and other common things- all of these being things that the common user will interact with! 

```javascript
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My Awesome Amazing Pinboard</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Bungee+Shade&family=Montserrat:wght@300&display=swap"
      rel="stylesheet"
    />
  </head>
```

This is one of the more simpler chunks of code from the project. This effectively created the *style* and *design* of the website. It created the font and the title, and a few other things. This, alongside other chunks of code worked together to create our website. 

```javascript 
[
  {
    "id": 1,
    "src": "https://mk0internationadm2x7.kinstacdn.com/wp-content/uploads/2018/10/ben-mullins-785443-unsplash-768x432.jpg",
    "tags": ["headphones", "smile"]
  },
  {
    "id": 2,
    "src": "https://i.pinimg.com/originals/2a/65/f3/2a65f33890ff03e08954a76d0a3d1865.jpg",
    "tags": ["headphones", "smile", "laptop"]
  },
  {
    "id": 3,
    "src": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfhYdIplE-UtslZHzzjdM5zJkCir1atAvgXg&usqp=CAU",
    "tags": ["laptop", "focussed"]
  },
  {
    "id": 4,
    "src": "https://miro.medium.com/max/10368/1*QDuUtggUKQxKA0pg8iCsyA.jpeg",
    "tags": ["laptop", "teamwork", "smile"]
  },
  {
    "id": 5,
    "src": "https://thegctv.com/wp-content/uploads/2018/11/BlackGirlsCode_main.jpg",
    "tags": ["laptop", "teamwork"]
  },
  {
    "id": 6,
    "src": "https://i.ytimg.com/vi/Q6NiqRqGePU/maxresdefault.jpg",
    "tags": ["laptop", "headphones", "focussed"]
  }
]
```

This longer and larger chunk of code is more complicated. It works to create the photos and the tags associated with them. It allows for the users to see the images and the tags associated with them. Other chunks of code allowed for them to interact with these added items, but I feel like I'd be crowding the entire blog at this point with nothing but javascript code. 

All of these chunks of code work together to effectively create the website. Whether they be creating responses to what button you click. Or they create a series of images for you to see. All of these are devoted to creating a effective user interface of sorts! It's essential for any website developer to know the basics of Frontend Development!

## Conclusion

After discussing all of this Frontend Development, it's obvious what I'll work towards next! Backend Development! Backend Development deals with the stuff that the user doesn't see, and instead deals with what the client/server/computer will see! It's the exact opposite of Frontend Development, ying and yang if you think about it. Both are needed, and both are exact opposites of one another. 

In the end, I learned how to write code to effectively create user interfaces and other interactive items on websites- also known as Frontend Development. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Blog Post #2

*"How does data flow from our computers to the drone? Describe each step of the process."* 

The computer flow is something like this:

Computer --> Internet --> Drones Access Port --> Internals (Drones Computer)

This is of course simplified. There's a million other things that the code most likely goes through before it actually hits the center of the drones stuffs. I shall now describe it more! It'll still be simplified though. 

The computer sends information from the program that we use (terminal and packet sender) through its own systems and then through its own exit ports. This stuff is basically shot out like a machine gun thanks to the UDP protocol we use. It finds the fastest way, but some data might be lost. This fast method allows for us to maintain a constant stream of commands to the drone, which is sent through its access port and stuff and then to its inner-workings. These inner-workings process the command and then act on the data from the command. THEN, the drone sends a checksum or something of that sort back to our computer. telling us that our command has been acknowledged. 
