# BOBFLIX

# Figma home page design
![image](https://user-images.githubusercontent.com/33323750/185719347-e9ab8960-053d-493e-a337-bae23169634d.png)

# Movie Carousel with pagination
https://user-images.githubusercontent.com/33323750/186016127-fd588f57-e27a-4fb0-98e2-9a21aad24941.mp4


# update 31/08 
finish slider and carousel container
but problem arise for fetching all data at once



https://user-images.githubusercontent.com/33323750/187803571-2c2265aa-f503-48b8-954d-2eb8677f642d.mp4

## optimize problem
one of the most importance in website is that keep the customer as long as posible and in NetFlix case we need to load a lot of image and can cause the website slow for customer to interact with example: 


https://user-images.githubusercontent.com/33323750/188248164-43d56ebe-2213-4206-a319-0d23d124ecdb.mp4

and as you can see user need to wait at least 5 second to be able to interact with website and also due to the image size is roughly 20Kb for each image and at the end we can see some image doesnt load  (we can down grade it but who dont want to go to a beautifull website rather than a blury one)
### Solution 
instead load all image at once only load the once that the user can see
change the fetch priority


https://user-images.githubusercontent.com/33323750/188248715-47920a27-9a5b-44df-b604-8f9532d440d7.mp4

