**Jasmin Moradia**
# Technical Resources:


1. Since our base idea is to make an artwork that needs an **AR engine** and different tools to incorporate **3D models**, I think we can use Spark AR in some way as it brings a lot of features that can help the pipeline. Also, it would solve the issue of platform as we can simple make an **instagram filter** which would take care of camera and gyroscopic data from a mobile device. I am experienced with making Instagram filters, and I know it helps in creative flexibility a lot. And for the coding part, **Spark AR supports javascript**, making it more aligned to EECS course requirements.

2. For the **sky replacement logic**, we can use **Luma/Color** keying which is simply an algorithm that masks out pixels of same kind i.e, brighter or blue colored pixels in this case. I think many art softwares can do that. I have achieved similar effect in Max while working on a DATT 1010 project. 

3. Apart from keying effect, **Max can be used for many purposes such as animation loops and sound creation**. So if there's a way we can create the logic network in Max and export the code version of it, this would unlock many more possibilities of creativity. (I know that **max can incorporate C++, NodeJS, Java and Javascipt**, but not completely sure if it can go the other way around.)

4. I get really amazed by **3D noise animations** and I think if we can add them to our artwork as a top layer where it changes according to **gyroscopic data**, it would make AR look more immersive like moving across cosmic space. This can be achieved using **Processing or Max**.

5. Talking about logic networks, using softwares that have **node-based programming style** can be of a huge benefit for us as I personally work with such softwares on a frequent basis. Hence, **Spark AR, Unity**, and Max are our potential options to think about.


# Aesthetic Resources:

1. **(https://www.instagram.com/coolacloy/)** The work from this creator is one my inspirations for this project. He does it using Adobe After Effects which makes a "guess" about camera's gyroscopic information to move around the animation in 3D space. I think we can produce more authentic results using actual sensor data from our mobile devices.

2.  **Cosmic Artworks from films such as Interstellar and Dr. Strange** really help my imagination. I was watching a documentary about how a few seconds of black hole animation took the creators months to program and make it mathematically perfect. It was so accurate that the creator wrote an actual paper about black holes.

3. Videos from **The Coding Train Youtube channel** help in artistic way as well. Since I am not from a coding background, I watch those videos to understand what things can be achieved via pure coding. This is how I got the idea of moving across **3D noise for star-like effect**.
Theres also a tutorial from the channel where an image/video changes to random numbers but you can still realise whats behind. Just like Matrix movie effect. Definately doable as we can changing realms in this project.

4. Audio plays an equally important part in immersive artworks and often gets neglected. I think for cosmic artwork, no music can compete to **Hans Zimmer's melodies** in Christopher Nolan's movies.

5. Recently, **AI art** is a hot topic in the art community. It keeps changing every moment and makes us question reality which makes sense for this project. 
https://aiartists.org/ai-generated-art-tools



**Xin Zhou**
# Technical Resources:
    Sky replacement:




    Phone connection: Gyroscope
        unity:  https://blog.csdn.net/wdjhzw/article/details/72842584
                https://docs.unity3d.com/ScriptReference/Gyroscope.html
        processing: 
                https://android.processing.org/tutorials/sensors/index.html

    Skybox:
        cloud:  https://openprocessing.org/sketch/126006
        star:   https://openprocessing.org/sketch/1433883





# Aesthetic:
    AR:
        Plan 1: replace sky to skybox
            https://instagram.com/coolacloy?utm_medium=copy_link
        Plan 2: show skybox 
            https://cs.xinpianchang.com/uploadfile/group/20141104/14150929875342.jpg
    Skybox:
        https://www2.kek.jp/ilc/wp-content/uploads/2018/10/michinokaimei_img1-1024x603.jpg

        img-qn.51miz.com/Element/00/74/00/81/1c25c4d7_E740081_372e8351.jpg

        https://pic57.photophoto.cn/20201028/0017030516308023_b.jpg



# Riordan Palmer
Aesthetic Resources:
1. Skymap is an AR program which displays the locations of stars in the  sky as well as offering the user ways to interact with it. We could use similar sky manipulation and look at how they built the interface. https://play.google.com/store/apps/details?id=com.google.android.stardroid&hl=
2. While we won't actively be using photoshop in our project, this kind of photo manipulation may help us write our code. https://www.youtube.com/watch?v=WKrkFfl8M6Q&ab_channel=PhotoshopTutorialsbyLayerLife
3. If we wanted to have objects with 3d elements on what would seem like a 2d plane (like the sky) this would be a neat idea. https://developers.google.com/ar/develop/augmented-images
4. The user interface is always an important part of any technology so this will help us pay special attention to that. https://xd.adobe.com/ideas/principles/emerging-technology/ux-design-principles-for-augmented-reality/
5. Similar to SkyMap this is another program which distinguishes the sky and displays important data on the screen. https://play.google.com/store/apps/details?id=com.ajnaware.sunseeker&hl=en_CA&gl=US

Technical Resources: 
1. While we would likely avoid frameworks like this as instead we would focus on our own coding, Wikitude may give us a good jumping off point for starting with AR. https://www.wikitude.com/products/wikitude-sdk/
2. It seems another good way of implement AR technology is image targets. Although this does not fit with the sky manipulation idea, we could use these as objects to place on the screen/sky. https://library.vuforia.com/features/images/image-targets.html
3. Plane Detection will be very important if we choose to make a program manipulating the appearance of the sky. By targetting places of high contrast, feature points are created to calculate surfaces. https://www.stereolabs.com/docs/spatial-mapping/plane-detection/
4. While this technology may not be available on all devices, depth sensoring would help greatly with seperating planes automatically. https://developers.google.com/ar/develop/depth
5. Debugging will undoubtedly be critical in developping our program so these resources will ensure we can find issues in our work. https://developers.google.com/ar/develop/debugging
=======
