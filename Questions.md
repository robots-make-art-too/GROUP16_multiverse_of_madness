Question about the technology of Sky Region Detection:

I did some research about the methods, and depend on our target and our programming level, I got following conclusion. I hope to discuss with everybody.

As we have shown we want the result that the sky is replaced by a skybox, but keep other enviroment objects on the screen.
As I know, commonly replacment software is based on 
1. Green-screen : our backgroud is unfixed, will not be green or any other specific colors. And that way is hard to identified details. So I think that one is not helpful for us.
2. Light and dark matting: same, because we need realtime replacement, and we are in real world, the light is unstable. So I don't think we can success base on light contrast.
3. Enhanced algorithm:
I fund some articles and tutorials explain Sky Region Detection 
    article: https://journals.sagepub.com/doi/pdf/10.5772/56884
    tutorial: https://blog.csdn.net/dulingwen/article/details/92993371
but the result from turtoial is not we want, we can see it still has some area of sky are not be identified. And for details, traverse the contours of course need time. Our project is realtime, it is not picture or video, as well our skybox is not a picture. So I think the using experience will not be very good.

4. AI: I believe we all can do it, but may not this project, not now....

Those are all my ideas about for this project. Based on our level, I can not find a prefect methods to meet our requirements. I hope to get some advices.






Solution Ideas:
If we can not get a prefect methods to replace sky, I have some opinions to do a little bit change to finish this project:
1. Triggered skybox by Image Target. Show skybox as a smaller model. We can go arround it to see the different faces.
2. Take the phone as the center point of skybox (we are in the center of skybox), turn the phone to see the whole scene.

We can make the skybox translucent, so we can see the real world as well, not like VR.