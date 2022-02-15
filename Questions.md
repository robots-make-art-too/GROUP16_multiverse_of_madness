Xin Zhou

Question about the technology of Sky Region Detection:
Hi everyone:
I did some research about the sky replacement, and depending on our target and our programming level, I came to the following conclusion. I hope to discuss it with everybody.

As we have shown we want a result that the sky is replaced by a skybox, but keep other environment objects on the screen.
As I know, common replacement software is based on 
1. Green-screen : our background is unfixed, will not be green or any other specific colors. That way it is hard to identify details. So I think that one will not get a perfect result for our project.
2. Light and dark matting: same, because we need realtime replacement, and we are in the real world, the light is unstable. So I don't think we can success based on light contrast.
3. Movement: We want to keep building as well, so that one is not fit.
4. Enhanced algorithm:
I found some articles and tutorials explain Sky Region Detection
    article: https://journals.sagepub.com/doi/pdf/10.5772/56884
    tutorial: https://blog.csdn.net/dulingwen/article/details/92993371
but the result from the tutorial is not what we want, we can see it still has some areas of sky that are not to be identified. And for details, traversing the contours of course need time. Our project is realtime, it is not a picture or video, as well our skybox is not a picture. So I think the using experience will not be very good.

5. AI: google has a very nice technology to find faces and some specific object, but not sky. I believe we all can do it, but may not this project, not now....

Sky replacement is a really good idea. But based on our level time and learning targets, I can not find a perfect method to meet our requirements. 
I hope to get some advice. 





Solution Ideas:
1. Rreplacing the whole sky perfectly is too hard to finish. But if we only replace the main part, then let the edges color become gradient color. That mean we need identify the highest or the most marginal part, for this we can use the tutorial link on the top. The result may be unnatural and slow. But this is the closest I can imagine of our idea and can improve accuracy.

If we can not get a perfect method to replace the sky, I have some opinions on do a little bit change to finish this project:
2. Triggered skybox by Image Target. Show skybox as a smaller model. We can go around it to see the different faces.
3. Take the phone as the center point of skybox (we are in the center of skybox), turn the phone to see the whole skybox world.

Those are all basic on my knowledge level. So should have more methods and I would like to discuss.